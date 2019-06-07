![HackaTAL 2019](https://raw.githubusercontent.com/HackaTAL/2019/gh-pages/HackaTAL_2019.png)

# Grand Débat // Legal Tech

## HackaTAL 2019
---------------
*(hackathon en traitement automatique des langues)*  
avec la conférence TALN/PFIA 2019

### Résumé

Tâches : analyses du grand débat / chatbots juridiques  
Site web : http://hackatal.github.io/2019  
Dates : 1 et 2 juillet 2019  
Lieu : Université Toulouse 1 Capitole  
Inscription : https://forms.gle/eNo8rogN2fWE3xedA (gratuite pr les étudiants / doctorants avant le 9 juin)  
Fil twitter : https://twitter.com/hashtag/HackaTAL2019  

### Le HackaTAL

Dans le cadre de la conférence TALN 2019 au sein de la plateforme PFIA, nous organisons la 4ème édition du hackathon en traitement automatique des langues, le HackaTAL 2019. L’objectif est de réunir les communautés scientifiques TAL, IA, et très largement au delà, autour de défis à relever pour questionner, interroger, modéliser, prototyper, coder, expérimenter, développer, tester, évaluer, échanger, etc. par équipes, dans une ambiance dynamique et sympathique :)

Les tâches proposées portent cette année sur deux thématiques (détails ci-dessous) :

- analyses des contributions au grand débat national
- conception de chatbots pour le domaine juridique

L’événement aura lieu cette année avec PFIA (https://www.irit.fr/pfia2019), à l’université Toulouse 1 Capitole, les 1 et 2 juillet 2019. Il est très largement ouvert à tous : juniors et séniors, informaticiens, linguistes, politologues, juristes, sociologues, etc. et ne nécessite aucune préparation particulière ni de compétences spécifiques... toute personne intéressée est bienvenue  pour apporter sa contribution aux travaux collaboratifs (par équipes) que nous réaliserons sur ces deux jours !

### Défis proposés

**1. Analyses du grand débat national**

Le « grand débat national » instauré par le gouvernement début 2019 s’est matérialisée par la mise en place de dispositifs contributifs (sites, réunions, cahiers de doléances), par lesquels les citoyens peuvent donner leurs avis en réponse à des questions, et/ou selon des thématiques. L’ouverture des données produites a donné lieu à la constitution d’un corpus volumineux, sur lequel des analyses peuvent être conduites, en particulier par utilisation d’outils de traitement de la langue ou d’analyse du discours. Les tâches sont très ouvertes, nous proposons en particulier une orientation sur la génération et la nature argumentative des contributions.

*Tâches*

- quantifier, analyser et visualiser les contributions au grand débat national
  - proposer des analyses sémantiques ou discursives des contributions
  - repérer et extraire des arguments structurés dans les contributions du grand débat
- générer des contributions ou des résumés
  - générer une proposition (phrase) à partir d’indices (mots, thèmes, opinions)
  - générer une synthèse à partir d’un ensemble de contributions

*Ressources*

- Jeu de données
  - https://www.data.gouv.fr/fr/datasets/donnees-ouvertes-du-grand-debat-national
  - https://granddebat.fr/pages/donnees-ouvertes
- Autres sites contributifs (à compléter)
  - Vrai Débat : https://le-vrai-debat.fr
  - Entendre la France : https://www.entendrelafrance.fr
- API GraphQL: https://granddebat.fr/developer
- Analyses existantes
  - Observatoire des débats (GIS Démocratie et Participation, ICPC, CEVIPOF) https://observdebats.hypotheses.org
  - Cartographies : Cartolabe (INRIA,  Paris-Saclay, CNRS) https://cartolabe-dev.lri.fr/map/debatt et Politoscope (CNRS) https://politoscope.org/le-politoscope
  - Annotations collaboratives du grand débat: https://grandeannotation.fr  et https://github.com/fm89/granddebat 
  - Projet Grande Lecture (bulles de filtre) : cartes de 100 contributions par circonscription http://www.grande-lecture.fr
  - Witted http://gdn.witted.tech
  - Democratie.app https://www.democratie.app
  - Grand Débat et TAL (Vincent Claveau) http://people.irisa.fr/Vincent.Claveau/GrandDebat et (Damien Nouvel) http://damien.nouvels.net/fr/debats2019
  - Gilets Jaunes (LERASS) https://www.lerass.com/wp-content/uploads/2019/02/GJ-V3.pdf


**2. Chatbots juridiques**

Depuis quelques années, la mise en place d’agents conversationnels (chatbots) par de nombreuses entreprises est une tendance de fond (et déjà sujet du HackaTAL en 2016, https://hackatal.github.io/2016). En parallèle, les outils numériques et technologiques sont toujours plus utilisés dans le domaine juridique (LegalTech). 

Ces deux évolutions technologiques permettent aujourd’hui d’envisager le développement d’agents répondant à des questions sur des problématiques juridiques. Les tâches proposées visent le prototypage, voire la mise en place (démos) de telles infrastructures de dialogue à partir de ressources, soit pour des problématiques liées à la vie courante des citoyens (recherche d’informations juridiques) ou dans un contexte de besoin de droit des innovateurs numériques, comme les participants d'un hackathon. 

En l'état, comme l'a démontré le premier baromètre sur l'accès au droit du Conseil National des Barreaux, l'émergence de la Legaltech n'a pas encore réellement permis de répondre de renforcer l'accès au droit et à la justice des français.  Le dernier écrivain public vient de prendre sa retraite, il est temps d'utiliser la technologie et les TAL pour fournir un assistant juridique virtuel pour les droits quotidiens des français. 

Lors du hackathon, 2 défis seront proposés :

- A partir des cas d'usages rencontrés par les acteurs de terrain de la médiation numérique (https://lamednum.coop) en matière d'accès au droit et avec les ressources mises à disposition par les partenaires du hackathon, créer un chatbot "écrivain public"
- À partir des cas d'usage rencontrés par les acteurs de l'innovation numérique et des ressources mises à disposition par les partenaires du hackathon, créer un chatbot sur les thématiques du droit des données et de la propriété intellectuelle. Ce deuxième défi trouvera une suite dans le Legal Hackathon organisé par l'ADIJ en septembre 2019 pour la création d'un code des activités numériques (http://www.adij.fr/code-activites-du-numerique-contributions/)

*Tâches*

- agent qui aide à la recherche d’informations juridiques et à la fourniture d'une information juridique personnalisée sur des besoins de la vie quotidienne (personnes en situation de handicap, parents isolés, droit de la famille, logement...)
  - détermination du besoin en droit en langage naturel
  - apporter un premier niveau de réponse à partir de réponses programmées à l'avance (par transformation dynamique de FAQ / forum en arbre décisionnel)
  - fournir des propositions de références (liens) vers des textes de loi pertinents et fournir un service de traduction automatisée de ces références juridiques en langage juridique "clair"
  - générer un modèle de courrier pour saisir l'administration et fournir les coordonnées du guichet administratif compétent
- agent qui répond à des questions des acteurs de l'innovation numérique pour développer un projet dans le respect du droit positif
  - détermination du cadre juridique applicable en fonction du projet
  - fournir proposition de références juridiques  (liens) et un service  de création d'un panier pour regrouper le droit applicable à la création d'un projet
  - fournir proposition de références juridiques  (liens) et un service d'aide à la mise en conformité via la détection de tâches à effectuer ( notamment sur le RGPD et le respect de la propriété intellectuelle des tiers)
  - générer des documents juridiques à partir des réponses aux questions du chatbot (voir par exemple https://app.aboutinnovation.com/Generateur-CGU, création d'un règlement de hackathon, aide aux choix des licences libres et ouvertes)

*Ressources*

- Droit du numérique : http://www.adij.fr/code-activites-du-numerique-contributions
- Droits quotidiens : les fiches en langage juridique clair de  https://www.droitsquotidiens.fr/fr et https://www.droitsquotidiens.be/fr
- Module de création d’assistant juridique (Seraphin.legal) https://www.legaltech.store/categoriesproduits/legal-bots
- Technologies  du réseau Legal Tech Lawyer disponibles pendant le hackathon https://www.legaltech.store
- Projet de chatbot juridique : https://leeally.com/fr
- Données et contenus juridiques https://www.data.gouv.fr

### Prix

Un panier de spécialités toulousaines solides et liquides sera offert aux meilleures équipes (vote des participants et organisateurs)

### Planning prévisionnel

**Lundi 1er juillet**

- 13h-14h : accueil et café (PFIA)
- 14h-15h : introduction, présentation du hackathon
- 15h-18h : développements en équipes
- 18h-19h : présentations invitées
- 19h-21h : cocktail (PFIA) développements en équipes
- 21h-??? : soirée dev chez Synapse (7 boulevard de la Gare, 31500 Toulouse)

**Mardi 2 juillet**

- 09h-12h : accueil, café (PFIA), développements en équipes
- 12h-14h : déjeuner et café (PFIA)
- 14h-16h : développements en équipes
- 16h-17h : présentation des résultats par équipe
- 17h-18h : vote, remise des prix, conclusion

### Organisation pratique

BYOD (amenez votre ordinateur)  
Pas de critères pour participer, le hackathon est ouvert à tous !  
Aucune préparation requise des participants  
Logiciels et données en ligne : https://github.com/HackaTAL/2019  

### Organisateurs

Julien Aligon (IRIT)  
Manon Cassier (AGORA)  
Chloé Clavel (Télécom ParisTech)  
Kevin Deturck (Viseo / ERTIM)  
Nicolas Dugué (LIUM)  
Maud Gilet (Seraphin.legal)  
Gibran Freitas (Seraphin.legal)  
Loïc Grobol (Lattice)  
Didier Ketels (Droits Quotidiens)  
Charles Leconte (Seraphin.legal)  
Hugues de Mazancourt (YSEOP)  
Emilie Merdy (Synapse)  
Damien Nouvel (ERTIM)  
Camille Pradel (Synapse)  
Thomas Saint-Aubin (Seraphin.legal)  
Raphaël Troncy (EURECOM)  
Guillaume Wisniewski (LIMSI)  
