---
title: "Représentation en 3D des objets d'OpenStreetMap"
authors:
    - Geotribu
categories:
    - article
date: 2015-02-03
description: "Représentation en 3D des objets d'OpenStreetMap"
tags:
    - 3D
    - OpenStreetMap
---

# Représentation en 3D des objets d'OpenStreetMap

:calendar: Date de publication initiale : 03 février 2015

***Article invité proposé par Clément Igonet***

![Logo OpenStreetMap](https://cdn.geotribu.fr/img/logos-icones/OpenStreetMap/Openstreetmap.png "OpenStreetMap"){: .img-rdp-news-thumb }

Depuis plusieurs années impressionné par les évolutions en terme de cartographie numérique, le projet [OpenStreetMap](https://www.openstreetmap.org/) me fait rêver tous les jours un peu plus à de nouvelles applications à portée de nos mains.  

Des plans de routes, des contours de bâtiment, leurs hauteurs, nombre d'étages, les types de toiture, les textures, les points d'intérêt, le projet Indoor... Énormément de choses ont déjà été imaginées par des passionnés qui contribuent progressivement au potentiel du projet OpenStreetMap.  

Ajoutons à cela la simplicité d'utilisation du format X3D (successeur de VRML, au format xml) pour la description de graphes de scène 3D et son implémentation WebGL avec la bibliothèque javascript x3dom maintenant supportée par la majorité des navigateurs web... Il ne reste finalement que peu de choses à faire pour une exploitation à grande échelle de la cartographie libre en 3D.  

Aussi, le fait d'initier le projet [osm2X3D](http://web.osm2x3d.net/) m'a semblé être une évidence.

----

## Qu'est ce qu'osm2X3D

Comme son nom barbare pourrait le laisser à penser, le coeur du projet osm2X3D a pour ambition de transformer des données au format OSM vers le format a X3D.  

J'ai alors codé en C++ un convertisseur de données, un peu dans le même état d'esprit que OSM2World, qui, rappelons-le, permet d'obtenir un ensemble d'objets 3D au format "obj" (wavefront pour être précis). Le gros avantage de X3D par rapport au format "obj" est de se placer un cran au-dessus: il ne s'agit pas simplement d'obtenir des objets 3D, mais bien de pouvoir interagir avec des objets d'une scène 3D, ce qui a déjà été déjà largement spécifié avec X3D.  

Le squelette du code C++ tient en quelques classes dont le contenu est relativement simple :

- Le monde 3D (world),
- le sol (ground),
- les bâtiments (building),
- les blocs spécifiques de bâtiment (building part),
- les étages (floor),
- les toits (roof),
- un convertisseur (converter)

Je n'ai eu qu'à intégrer tout ça avec la lib js x3dom, secouer tout ça, et ça donne la démo suivante: <http://web.osm2X3D.net>.

![osm2X3D](https://cdn.geotribu.fr/img/articles-blog-rdp/capture-ecran/osm2x3d.png "osm2X3D"){: .img-center loading=lazy }

Bien sûr, il ne s'agit là que d'une première avancée. Pour un meilleur rendu 3D, et à moindres frais, il reste à prendre en charge:

- les différents types de toitures,
- les textures de bâtiment.

Ultérieurement, on peut aussi imaginer la prise en compte des élévations de sol par exploitation des données mises à dispositions (CCCOT, IGN, NASA, etc...)

## Ambitions Indoor et B2B

En terme d'interaction avec la scène 3D, et à très peu de frais, il est déjà possible de naviguer de manière assez intuitive. Un clic souris sur un objet de la scène (bâtiment ou étage) permet de focaliser la vue/navigation sur cette objet.

Pour le reste, tout reste à faire. "Tout", qu'est-ce à dire? Hé bien l'ambition "cachée" du projet est de permettre une navigation jusqu'à l'intérieur des étages des bâtiments. Et c'est là que tout reste encore à imaginer.

La première orientation que je prends, c'est de m'appuyer sur des projets tels que [IndoorOSM](https://wiki.openstreetmap.org/wiki/IndoorOSM) ou [Indoor Mapping](https://wiki.openstreetmap.org/wiki/Indoor_Mapping).  

Une autre orientation, plus "B2B" est de s'appuyer sur une source tierce de données avec des fonds de plans dans un format ouvert et standard (SVG) et des implantations de points (P.O.I.) dans ces plans. Cette orientation convient certainement plus à des applications offline et plus ou moins privées:

- détection incendie,
- galeries marchandes,
- agences immobilières,
- offices HLM,
- etc...

## Navigation dynamique

Une autre orientation du projet, à destination du grand public, est de mettre à jour dynamiquement la scène 3D sous forme d'intégration de flux de données OSM. Les spécifications X3D et la mise en œuvre avec x3dom permettent cette gestion dynamique de la scène 3D. Cela concerne notament les données suivantes:

- fonds de plan (tile),
- infos de bâtiments,
- élévation de sol.

## Join us

Enfin... Je devrais plutôt dire "join me" pour l'instant. Comme vous l'aurez peut-être compris: yaplukafocon ! La porte est grande ouverte à tout contributeur dans le cadre d'un projet libre (projet sous licence GPLv3 - GitHub : [osm2X3D](https://github.com/clement-igonet/osm2x3d)).  

Je suis par ailleurs activement à la recherche de contributions financières pour faire évoluer le projet dans un cadre pro.

----

## Auteur {: data-search-exclude }

Article invité proposé par Clément Igonet.
