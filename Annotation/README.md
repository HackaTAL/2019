# Outils d'annotation du Grand Débat
L'outil préconisé pour l'annotation est [Brat](https://brat.nlplab.org).
## Installation de BRAT
La procédure d'installation est détaillée [ici](https://brat.nlplab.org/installation.html). Le mode d'installation préconisé est le mode *standalone*.
### Définition du schéma d'annotation
Le schéma d'annotation de Brat est contenu dans le fichier `annotation.conf` du répertoire d'installation de Brat. Remplacez le contenu de ce fichier par les lignes suivantes:

```
[entities]

Connecteur
Conclusion
Premisse

[relations]

Lien_logique    Arg1:Premisse, Arg2:Conclusion, <REL-TYPE>:transitive
Lien_logique    Arg1:Connecteur, Arg2:Conclusion, <REL-TYPE>:transitive
Lien_logique    Arg1:Connecteur, Arg2:Premisse, <REL-TYPE>:transitive 

[events]
[attributes]
```

### Installation des échantillons du Grand Débat
Placez-vous dans le répertoire d'installation de Brat et extrayez l'archive `hackatal.tar.gz`. Cela va faire apparaître une "collection" *Hackatal-GDN* dans la liste de collections de Brat, avec des fichiers numérotés de 1 à 10.

You're ready to go!
## Transmettre les annotations au leaderboard
Il vous suffit de télécharger sur le leaderboard les fichiers `.ann` dans le répertoire de votre équipe. Si vous utilisez un autre outil d'annotation, merci de transformer vos annotations au [format Brat](https://brat.nlplab.org/standoff.html)

## Précautions par rapport à l'utilisation de Brat
Si vous désirez intégrer vos propres documents pour annotation dans Brat, il faut savoir les choses suivantes:

1. le lien d'*upload* de l'interface Brat ne fonctionne pas, il faut importer directement des fichiers `.txt` dans un sous-répertoire de `data`pour crééer une collection,
2. Plusieurs contributions à annoter peuvent être regroupées dans un même fichier texte, mais les frontières de documents doivent être marqués car Brat coupe les textes en phrases. La convention, dans les fichiers échantillon, est de les délimiter par une ligne contenant `##doc`
3. Brat n'accepte de lire la collection que si les fichiers `.txt`sont accompagnés de fichiers `.ann`, fussent-ils vides. La commande suivante crée (si nécessaire) les fichiers en question pour chaque fichier `.txt` depuis le répertoire d'installation de Brat.

```
find data -name '*.txt' | sed -e 's|\.txt|.ann|g' | xargs touch
```
 