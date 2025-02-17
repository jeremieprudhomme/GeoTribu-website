---
title: "Interview de Drones Crisis"
authors:
    - Geotribu
categories:
    - article
date: 2014-08-20 11:20
description: "Interview de Drones Crisis"
tags:
    - drone
    - interview
    - OpenStreetMap
---

# Interview de Drones Crisis

<iframe width="100%" height="400" src="https://www.youtube-nocookie.com/embed/H2sxUHeqB8g" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Partie 1 - Retour d'experience sur le projet Drone Adventures

### 1. (All) Pourriez-vous svp vous présenter brièvement (âge, études, parcours, projets, produits, compétences) ?

Emmanuel de Maistre : Normalien et HEC Entrepreneurs, Dirigeant et co-fondateur de Redbird (opérateur de drones depuis fin 2012) et Président de la Fédération Professionnelle du Drone Civil (FPDC) crée en juillet 2013.

### 2. (Frédéric/Adam) Pour commencer, pourriez-vous nous décrire le projet Drone Adventures et plus particulièrement votre mission en Haïti? _(contexte, objectifs, déroulement)_

(Adam) : Drone Adventures est une association fondée en Suisse début 2013 avec le but de promouvoir les utilisations civiles de drones, notamment dans les domaines de l'humanitaire, la conservation, la culture (archéologie, tourisme, etc) et dans la réponse rapide aux urgences.  Notre but est de présenter la technologie de drone à travers des missions phares que nous organisons aux 4 coins du monde et sur lequel nous communiquons par la suite à travers des vidéos, des images et des articles publiés sur internet.  Nous ne voulons pas vendre du rêve de ce qui est possible en 10 ans; nos missions poussent la limite de la techno, mais montrent surtout ce qui peut être fait aujourd'hui, avec la technologie existante déployer dans le terrain pour des buts utiles.  Pour tous nos projets c'est surtout important d'avoir un partenaire dans le terrain pour lequel le travail que nous faisons leur aide à mieux faire leur travail.

La première mission de Drone Adventures était dans le domaine de l'humanitaire.  Nous sommes parti en Haiti pour une semaine de cartographie aérienne intense pour soutenir et promouvoir les efforts de nos partenaires de terrain, Fred avec l'IOM et OSM, qui sont actifs sur le terrain depuis plusieurs années déjà.

FredM: : Initialement, nous avons commencé à faire des photographies aériennes avec des drones, en 2011,  avec l'office international des migrations en Haiti, pour cartographier les zones à forte densité de population et de bati (bidonvilles et zones de montagne) à Port Au Prince et alentours.

Nous avions besoin d'images plus précises que les images satellites et prises juste avant d'envoyer les equipes sur le terrain, pour réaliser des travaux de mitigation, de recensement de la population.

Par la suite nous avons mis à disposition ces images pour la communauté Open Street Map (OSM)  et la réalisation de cartopartie en Haiti.

En effet l'utilisation d'UAS et de systèmes d'information géographiques Open source lors de « Carto partie OpenStreetMap » permet à la communauté locale de s'impliquer et de discuter dans le quartier, le village, la ville autour de la cartographie comme point de départ d'initiatives plus larges pour répondre aux besoins identifiés localement.

Open Street Map france a pu héberger ces images aériennes sur leur serveur (jean guilhem, qui avait fait aussi la campagne de points GPS differentiel avec le CNES en 2012) , permettant aux contributeurs OSM et acteurs humanitaires d'utiliser ces données facilement.

!!! tip Ressources complémentaires
    - [Rapport de la mission en haiti, en plus de la video](https://drive.google.com/file/d/0B23KlWXOmZhJQVdTQXY5aWNMUVU/edit?usp=sharing)
    - COSMHA et cartographie communautaire grace au images UAV. A la suite des images faites par Drone Adventures/IOM,  il y a eu une cartopartie avec les communautés locales et C-OSM-HA sur la zone de Onaville avec les communautés et OSM Haiti (COSMHA) : [lire le compte rendu](http://ovh.to/QmPf2hC)

### 3. (Frédéric/Adam) Quels ont été les points forts des drones pour cette mission? Pourquoi le choix des drones plutôt que d'autres vecteurs aériens (ULM, avion, etc)?

(Adam) Il y a plusieurs points clés qui donnent l'avantage aux drones par rapport aux avions ou satéllites pour la cartographie immédiate :

- Facilité d'utilisation et intelligence embarqué: des drones professionnels de type eBee sont autonomes et intelligent au point qu'il faut très peu de connaissance pour les utiliser.  Les plans de vols se planifient automatiquement à partir d'une zone d'intérêt, même en 3D.  Ils décolent, volent, prennent des images et atterrissent tout seuls.
- Rapidité: Le temps de déploiement d'un drone se compte en minutes.  Les images peuvent être dans les mains de l'utilisateur dès l'atterrissage du drone.
- Sûreté: Il y a un fort axe sur la réaction aux erreurs dans l'autopilote de l'eBee.  Tous les capteurs et l'état du drone sont constamment contrôler, et des dizaines d'erreurs possibles sont gérer de manière intelligente. En plus, à 700g, la légerté de l'eBee présente un danger très minime aux gens et les infrastructures sur lequel il vole, même dans le cas d'une éventuel chute. (j'ai fait des tests sur le swinglet cam qui fait 500 gr et qui a une petite surface alaire, et tombe de façon oblique en planant.

FredM:

- Facitlité d'utilisation: une prise en main d'une quinzaine de minutes suffise pour le faire décoller et parametrer le plan de vol. Cela ne remplace cependant pas l'experience et la formation pour que tous les vols se passent  bien. Si il y a un probleme c'est souvent a cause d'erreur de manipulation de l'operateur. Nous insistons donc sur la formation des pilotes UAV.
- Le coût : les images sont de trés bonnes qualités cela permet de cartographier précisement la zone avant d'envoyer une equipe sur le terrain.
- Le traitement des images est facilité par le logiciel Pix4D, auquel nous allons ajouter un mini serveur portatif pour limiter le temps de traitement et pouvoir diffuser les images sur plusieurs ordinateurs simultanéments. Il ne manque plus que des panneaux solaires pour etre completement autonome sur le terrain.
- Les conditions météo: Le vent est un handicap, on peut voler avec des vents a 30-40 km/h apres cela devient difficile. Cependant on peut voler sous une couverture nuageuse, ce qui peut etre utile parfois lors du passage d'un cyclone ou d'inondation.

### 4. En terme de logistique et de mise en œuvre, combien de temps prend le paramétrage d'une mission?

(Adam) Tout dépend de la complexité de la zone.  Pour la plupart des situations le planning est automatique et peut être fait en quelques minutes.  Le logiciel peut même diviser des zones d'intérêt en plusieurs zones si un seul vol ne suffit pas.  Par exemple, sur la cartographie de Fort Liberté au nord de Haiti nous avons volé avec trois drones en même temps pour réduire le temps necessaire pour prendre les images.

Ce qui peut prendre du temps, surtout pour les drones à aile fixe, c'est de trouver un endroit assez grand pour attérir.  Un eBee par exemple a besoin d'environ 80m d'espace en longueur sans obstacles.  Cela a surtout difficile pendant les vols que nous avons fait dans les zones urbaines dense de Port-au-Prince, où les endroit ouvert sont difficile à identifié à travers des cartes de satellite qui sont parfoit assez anciens.

FredM :

- Apres le passage de Sandy en Novembre 2012,  nous avons pu faire voler et parametrer la mission sur place, nous avons ainsi pu  disposer rapidement d'image avant et aprés, pour réaliser les premieres analyses.
- Le ebee permet maintenant d'atterrir non pas en faisant des cercles autour du point de decollage, mais en ligne droite face au vent, c'est une option importante en zones urbaines, ainsi que le capteur optique qui permet de gerer les distances par rapport au sol lors de l'atterrissage et ainsi ralentir l'appareil.
- Autorisation: meme si nous avons des autorisations officielles, nous prenons le soin de prevenir la population (responsable local) et de les associer au prise de vue, dans le cadre d'OSM on réalise souvent des cartoparties avec les communautés locales, aprés. Nous avons fait cela lors du cyclone Sandy, en proposant aux responsables communautaires de participer à l'amelioration de la carte sur son secteur.

### 5. (Frédéric/Adam) Pour que les auditeurs comprennent, pourriez-vous nous décrire rapidement toute la chaîne de traitement de l'acquisition des images  à leur utilisation?

(Adam) Typiquement ça commence avec la définition de la zone d'intérêt.  Ca peut être un quartier d'une ville, la ravine d'une rivière, le bord de la mer après un ouragan.  Un polygone est dessiné dans le logiciel eMotion qui est livrer avec l'eBee, et une résolution est défini, par exemple 10cm.  Le logiciel ensuite calcul le chemin à prendre pour le drone, les altitudes des waypoints, les points où il faut prendre les photos, bref tout les détailles du vol.  Il faut ensuite choisir un point d'atterrissage après la mission.

Une fois dans le terrain il faut sortir le drone (ou les drones) de sa valise, attacher les ailes et brancher la batterie.  Le drone fait une séries de tests automatiques de ses capteurs et attend un fixe de GPS.  Il faut aussi sortir l'ordinateur ou la tablette, brancher la radio par USB et se connecter avec le drone avec eMotion.  Le plan de vol va être charger automatiquement sur le drone.

Une fois un GPS acquis, on prend le drone entre deux mains, on le secoue trois fois pour démarrer le moteur, puis on le lance, et c'est tout!  Le drone vol ça mission, prends les photos et reviens au sol quand la mission est fini.  L'opérateur peut à tout temps adapter la mission, envoyer des commandes si necessaire.

Après l'atterrissage les images et le fichier 'BlackBox' qui contient les données du vol sont copier sur l'ordinateur, puis le traitement d'image avec PostFlight Terra peut commencer.

FredM: Oui c'est la partie la plus dur, …. apres il faut le suivre des yeux durant toute la mission.

### 6. (Pix4D) Comment se déroule le traitement des images obtenues ? Quelles sont les informations qu'il est possible d'obtenir (images, MNT, contour, etc.)

Le logiciel développé par Pix4D permet de convertir plusieurs milliers d'images prises par différents drones, avions ou hélicoptères en orthophotographies et modèles 3D géoréfférencés.

Géomaticiens et utilisateurs lambda peuvent ainsi bénéficier de résultats précis leur permettant de mesurer distances et volumes afin d'analyser l'environnement observé.

La technique utilisée tire parti d'une combinaison experte entre la photogramétrie traditionnelle et les techniques avant-gardiste du domaine de la vision par ordinateur ou "computer vision".

1. Suite au travail de terrain :
    - Chargement des images
    - Reconnaissance automatique de la caméra (pas de calibration particulière).
    - Reconnaissance automatique des coordonnées géographiques associées à chaque prise de vue.
2. Si disponible, les points de controle au sol (GCP) sont intégrés afin d'améliorer la précision des résultats et leur géoréférencement.
3. Le Processus est lancé en un seul clic
    - Calibration, Optimisation, Génération du rapport de qualité...
    - Densification du nuage de points
    - Génération du Modèle Numérique d'Elévation et de Ortophotographie (1-3 pixels d'exactitude GSD=2 cm \&gt; 2 à 6 cm de précision)

!!! info
    Consulter [la documentation officielle sur la précisionle support](https://support.pix4d.com/entries/27021968-Accuracy-of-Pix4uav-outputs)

#### Présentation des fonctionnalités les plus courantes

- Calcul des distances, des volumes
- Annotation d'objets sémantiques
- Correction des distorsions sur les angles des bâtiments, suppression d'éléments gênants (voitures en mouvements) au sein de l'orthophoto
- Réutilisation des résultats dans un workflow métier SIG et/ou DAO

!!! info
    Consulter [la documentation officiel sur le sujet](https://support.pix4d.com/hc/en-us/articles/202558499-Pix4D-outputs-with-other-software-by-output)

#### Nouveautés

- Retravailler au sein du nuage de points et des images en soit (cf. rayCloud plus loin) pour examiner le modèle et affiner le positionnement des Points 3D parmi l'ensemble des prises de vues disponibles.

- Video of rayCloud

### 7. (Pix4D) Quelles différences ya t'il entre le traitement d'images qui se fait classiquement (ex avion) et celui par drones ?

La photogrammétrie et la vision par ordinateur ont en commun le fait qu'elles effectuent une recherche de mesure 3D à partir d'images permettant la stéréoscopie.

La photogrammétrie est un domaine mature, employé depuis le 19ème siècle proposant des résultats précis issus d'une chaine de traitement robuste et industrialisée associée à des caméras et capteurs haut de gamme (Le prix de la référence dans le domaine s'élève à 1M€ + Heures de vol) combinant:

- haute résolution,
- parfaite calibration,
- précision optimale du géopositionnement et de l'orientation de chaque prise de vue.

En revanche, le traitement d'images réalisé suite à une acquisition par UAV est lui, plus souple, et accessible pour cartographier des territoires de plus faible superficie.

Même s'il doit composer avec des informations beaucoup plus aléatoires telles que:

- Absence ou inexactitude des données GPS et d'orientation relative des images
- Axes de prise de vue obliques
- Divers appareils photo grand public non calibrés et aux filtres souvent intrusifs (contrastes, saturations...)

Le traitement automatique des d'images par Pix4D est rendu possible grâce un recouvrement plus important ainsi qu'à l'aide d'une quantité de données plus importantes.

La photogrammétrie traditionnelle tente de produire la meilleure cartographie possible avec un nombre minimal de photos via l'utilisation  de moyens et d'équipemment haut de gamme.

**Note:** La technique utilisée par les logiciels tels que Pix4D permet de traiter les images provenant de drones, mais aussi d'avions ou d'hélicoptères. L'inverse est, lui, plus difficile.

### 8. (SenseFly/Pix4D) Quels ont été les défis technologiques auxquels vous avez dû répondre?

(Adam)

- Intelligence artificielle: gérer un vol d'une manière automatique du décolage à l'atterrissage basé seulement sur les capteurs de l'autopilote.  L'atterrissage linéaire avec une descente à 20 degrées et une précision de 5m est que possible à cause de notre expérience en capteurs optique, gagné à travers plusieurs thèses doctorales.

- Facilité d'utilisation: les clients de senseFly ne sont pas des modélistes.  Il faut que le drone peut être utiliser par le grand publique sans nécessiter des formations complèxes et surtout sans savoir piloter un modèle réduit!  Nous développont continuellement des outils pour facilité la tache de planification et surveillance de vol.  Notre dernière mis-à-jour a notamment rajouté la visualisation de vol en 3D et l'adaptation du plan de vol à la base d'un modèle d'élévation de la terre, une outil clé pour tout ce qui est vol en terrain montagneux.

- Sûreté et fiabilité:  Les clients de senseFly dépendent sur l'eBee pour faire tourner leur entreprise.  Ils veulent faire des dixaines voir des centaines de vols avec leur drone jour après jour sans besoin de réparation, des glitchs de logiciels, et tout ça dans des conditions météorologiques et géographiques difficiles.  Nous avons des histoires de drones qui ont fait plus de 300 vols sans maintenances.  Des eBees volent dans des vents de 40km/h, et ont même volé à plus de 5000m d'altitude pendant la dernière mission de Drone Adventures qui a cartographié le Cervin en Suisse.

(Pix4D)

- Mise en œuvre d'algorithmes complexes tirant parti de la solidité et de la maturité de la photogrammétrie sur laquelle sont venus se greffer les techniques issues du "computer vision" afin de proposer une plus grande souplesse d'utilisation. (eg. Prise de vue oblique notamment)

- Proposer une interface ergonomique et simplifiée à nos clients tout en proposant l'obtention de résultats pertinents et de qualité comparables - voir supérieurs, à ceux proposés par les techniques traditionnelles. (Total station vs UAV)

- Diversité des drones et des caméras associées : RGB, NIR,  IR, FishEye, tetracam, GoPro… avec lesquels nos clients peuvent aujourd'hui travailler.

- Etre à l'écoute d'une diverssité d'utilisateurs composé de professionnels géomaticiens experts ou naissants, à travers le monde, s'intéressant à la cartographie par le biais des UAV. (eg. ESA et monsieur tout le monde \&gt; autrefois inaccessible)

- Proposer un processus plus complet à l'utilisateur lui permettant de mieux tirer parti de la relation entre le nuage de points et des images afin d'affiner les objets 3D et le résultat final. (cf.rayCloud)

### 9. (Fédération française du drone civil) Avez-vous connaissance d'utilisation similaire des drones pour la cartographie d'urgence en France ? Pourriez-vous nous donner des exemples/expériences d'utilisation des drones (surveillance des incendies, foules, etc.)

(PIX4D)

- Glissement de terrain

[http://www.youtube.com/watch?v=lBzdqHGFhBU?rel=0&amp;showinfo=0&amp;controls=1&amp;hd=1&amp;autoplay=1](http://www.youtube.com/watch?v=lBzdqHGFhBU?rel=0&amp;showinfo=0&amp;controls=1&amp;hd=1&amp;autoplay=1)

Contexte : <http://www.pix4d.com/in-terra-ltd/>

Informations techniques : <https://support.pix4d.com/entries/24738312-Landslide-in-Switzerland>

- Expertise d'une scène de crimes, accident, prise d'otages_

Exemples d'actions menées par ConservationDrones <http://3drobotics.com/2013/11/drones-save-endangered-species-and-forests/>

### 10.  (Drones Adventures/Pix4D) Quelles ont été les limites observées lors de l'utilisation des drones lors de missions de cartographie d'urgence ? Sont-ils le meilleur moyen d'obtenir une carte ? Doivent-ils être combinés à d'autres mode d'acquisition de données ?

(Adam) Pour moi la limite des drones dans la cartographie est surtout dans la taille de surface.  Les cartes d'haute résolution créé par des drones sont complémentaires aux carte de grande zones pris par des satéllites.  Une autre limite reste la météo, surtout le vent, en sachant que quand il pleut les satélittes ne peuvent pas non plus faire des cartes à cause des nuages.

De mon point de vue nous pouvons encore travailler sur la vitesse avec laquel les orthomasaics peuvent être mis dans les mains des gens qui en ont besoin.  Le temps que le drone arrive sur le terrain, qu'il fini sont vol, que les photos sont traitées en orthomosaic et puis diffuser aux utilisateurs (par internet par exemple) se compte toujours en heures, parfois même en jours.  Je ne crois pas que cela est une limite par contre; l'optimisation de cette chaine est en cours, autant par les fabriquants de drone comme senseFly que les développeurs de logiciels comme Pix4D et je crois bien que nous y arriverons dans les années (ou même les mois) qui viennent.  Il y a déjà des exemples de cartographie en real-time dans la domaine académique, comme dans ce projet en Autriche:

<http://www.lakeside-labs.com/research/collaborative-aerial-robots/>

(Pix4D) Le temps de calcul mentionné par Adam est un défis technologique sur lequel nous travaillons en priorité et ce pour chacun de nos développements.

----

## Partie 2 - Discussion ouverte sur l'usage des drones pour la cartographie d'urgence

### 11. (Fédération Professionnelle du Drone Civil) Pour commencer cette discussion ouverte, faisons un point sur le vocabulaire. Drone, UAV, UAS RPAS est-ce la même chose ? Quel terme faut-il utiliser ?

C'est encore vague. Le consensus international se dirige vers l'utilisation du terme RPAS. La règlementation francaise DGAC utilise d'ailleurs le terme "aéronefs télépilotés". UAS est encore largement utilisé dans l'industrie. "Drones" a une connotation militaire dans le monde anglo-saxon et aux USA. Le même terme "drone" n'a pas cette image négative en France et est largement utilisé par les journalistes notamment car plus court et plus frappant que "RPAS".

### 12. (Fédération Professionnelle du Drone Civil) Afin que les personnes qui nous suivent comprennent, pourriez-vous nous faire une rapide typologie des différents drones (ex: Micro Air Vehicles, LALE, MALE, HALE)

En France la  règlementation a défini différentes classes de drones, de 0 et 150 kg. Les grands seuils sont : de 0 à 2 kg, de 2 à 4 kg, de 4 à 25 kg et de 25 à 150 kg.

Les Micro-drones et/ou mini-drones pèses entre 2 à 25 kg environ, utilisés par les armées et le monde civil.

Les HALE, MALE sont catégorie de drones de longue endurance et moyenne ou haute altitude, réservée aux militaires.

### 13. (All) Quels sont les autres domaines d'actions possibles pour l'utilisation des drones, pourriez-vous nous donner des exemples

(Pix4D)

- Suivi des constructions

- Gestion des carrières et gestion des volumétries (calculs de stock, impératifs légaux)

- Agriculture et application spécifiques liées au suivi des cultures (cartes de vigueur du végétal, NDVI)

- Gestion de l'environnement et intervention en cas d'urgence

- Cinéma et photographie aérienne

- Gestion de la quatrième dimension afin de proposer des cartes d'évolutions

(FPDC)

Marché les plus mûrs : topographie, cartographie et inspections d'ouvrages d'art. Suivent l'agriculture (cartes de croissance des végétaux) et la surveillance et maintenance industrielles de réseaux (éléctricité et énergie, pétrole-gaz, rails-routes)

- corridor mapping (référentiel infrastructure)

- inspections d'ouvrages (ponts, barrages, éoliennes, etC.)

- agriculture (NDVI)

### 14. (SenseFly/Fédération Professionnelle du Drone Civil) Les drones soulèvent de nombreuses questions juridiques, respect de la vie privée etc. pourriez-vous nous faire un rapide état des lieux de la question en France et plus globalement à l'international ?

Très intéressant article sur ce sujet : [http://www.wilsoncenter.org/publication/tweeting-storm-the-promise-and-perils-crisis-mapping](http://www.wilsoncenter.org/publication/tweeting-storm-the-promise-and-perils-crisis-mapping)

[http://www.wilsoncenter.org/sites/default/files/October_Highlight_865-879.pdf](http://www.wilsoncenter.org/sites/default/files/October_Highlight_865-879.pdf)

Dans le cadre commercial tel qu'il est actuellement défini en France, cette question est un non-débat. Il est en effet actuellement interdit de survoler des zones peuplées ou des habitations sauf dans le cadre du scénarion "S3" qui est très encadré règlementairement, notamment au travers d'autorisations préfectorales. Il n'est pas possible de survoler une propriété privée (particulier ou entreprise) sans l'accord des propriétaires. Un opérateur qui contrevient à la règle est hors-la-loi. Par ailleurs, tout opérateur de drone est soumis aux mêmes règles que toute personne qui réalise des prises de vue aériennes avec notamment des déclarations préfectorales.

(Adam) Au niveau internationale, la légistlation est différent dans chaque pays du monde et varie entre les pays assez permissifs, où les drones sont soumis au mêmes règles que les modèles réduits, jusqu'à l'interdiction preque absolue d'utilisation commerciale, comme la situation actuel aux Etats Unis.  En règle générale, y a peu de pays où c'est possible de voller hors de portée de vue.  senseFly vends des drones dans des dizaines de pays différents, et nous travaillons avec nos revendeurs pour mieux comprendre et rendre nos appareils conforme aux lois locaux.

Les règles sont en générale basé sur des questions de sûreté plutôt que de vie privé.  Même si la vie privé est une question très importante, il faut surtout assurer que les drones ne vont pas mettre en danger les autres acteurs de l'espace aérien et les gens aux sol.  Les questions de vie privé vont être encore débatu pendant un long moment.

### 15.  (Fédération Professionnelle du Drone Civil) En France, malgré les deux arrêtés du 11 avril 2012, il existe un vide juridique concernant les drones. Par exemple, à l'heure actuelle, il n'existe aucune distinction entre les drones de loisirs (DJI Phantom, etc.) et les drones civils professionnels.  Pensez-vous que cela va évoluer et si oui dans quel sens ?

C'est faux, il existe une distinction nette entre les "aéromodèles" (catégories A et B de l'arrêté d'avril 2012) et les "aéronefs télépilotés" (drones commerciaux, catégories C à G de l'arrêté d'avril 2012).

La règlementation francaise va évoluer courant 2014. Quelques améliorations de poids ou de distance mais également des contraintes pour augmenter la sécurité.

### 16.  (Fédération Professionnelle du Drone Civil) Pourriez-vous nous dire quelques mots à propos de la première assemblée générale de la Fédération Professionnelle du Drone Civil  qui a eu lieu au début du mois de Novembre ? De plus, comment expliquez-vous le dynamisme français dans le domaine ?

Lien : [http://www.helicomicro.com/drones-le-point-de-vue-des-pros/](http://www.helicomicro.com/drones-le-point-de-vue-des-pros/)

La Fédération compte environ 280 adhérents répartis partout en France. Ce sont principalement des constructeurs, des opérateurs et des grands donneurs d'ordres comme SNCF, EDF ou GRT Gaz.

La première assemblée générale de la FPDC a été un succès avec la présente de plus de 150 personnes dans les Salons de l'Aéroclub de France sur Paris. Nous avons voté le renouvellement du bureau, le budget, et l'adhésion des opérateurs à une "charte de bonnes pratiques". Plusieurs interventions de la DGAC et de UVS International par ailleurs.

### 17.  (Pix4D/SenseFly/Fédération Professionnelle du Drone Civil) Le marché des drones civils est en plein boom avec de fortes perspectives de croissance. Quelles ont été les raisons de cet engouement ?

(Adam)

- miniaturisation des capteurs et processeurs puissants necessaires pour la robotique suite au marché de téléphone portable
- des drones plus adaptés et optimisé à des utilisations précis (plutôt qu'un drone sur lequel l'utilisateur dois mettre son propre capteur)
- Planification du vol aisée et rapidité d'acquisition des données

(Pix4D)

- Fiabilité et précision des résultats obtenus ainsi que leur intégration au sein de processus de travail plus complets GIS ou CAD
- Coût d'investissement initial moindre comparé à ceux nécessaires pour un projet de photogrammétrie traditionnel
- L'existence de _package_ proposant à la fois les drones mais aussi des logiciels performants pour planifier les vols et traiter ultérieurement les images obtenues.

(FPDC)

- la bonne image du drone en France de manière générale, popularisée par Parrot et l'AR.Drone qui s'est vendu à 500.00 exemplairs
- la bonne image auprès des médias généralistes comme spécialistes et un fort engouement médiatique
- la règlementation accessible et qui permet l'opération de drones même pour des investissement réduits (le loisir)
- mais il ne faut pas se cacher, le marché du drone en France c'est un marché de "médias / communication" actuellement, en transition progressive vers un marché industriel

### 18.  (All) À court, moyen et long terme que prévoyez-vous pour le domaine du drone civil (vous pouvez également parler de vos prochaines versions/drones, etc.) ?

(Adam)

- de plus en plus d'automatisation dans des taches difficiles, moins besoin d'intéraction d'utilisateur, jusqu'au niveau de système qui s'intègre à l'infrastructure, se déploient et se rechargent eux-mêmes
- acceptation de la technologie au niveau publique et légistlatif
- pleins de jolies nouveaux drones de senseFly :)
- (Pix4D) Explosion du marché pour les particuliers avec des interfaces simplifiées
- (Pix4D) Fonctionnalités toujours plus adaptés aux besoins des professionnels selon des thématiques de métiers toujours plus variées

(FPDC)

Un ré-équilibrage du marché entre les applications "médias" et les applications "industrielles", les secondes étant appellé à se développer de plus en plus.

Une évolution de la structure du marché en lui-même avec le développement d'opérateurs leaders possédant la taille critique nécessaire pour répondre à de grands marchés à l'échelle nationale. Le regroupement d'opérateurs indépendants.

Un développement progressif des capacités de traitement des données issus de drones (logiciels, ingénieurs, etc.)

Une augmentation des poids et des distances autorisées sous réserve de contraintes de sécurité.
