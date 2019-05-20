# ++Formation-action de médiation à la donnée++
**==++Arsenic + Datactavist++==**

**Document formation :** https://datactivist.coop/arsenic_meddata/index.html

**Mail du formateur :** Samuel G. samuel@datactivist.coop

**Mails des participants :**
- Anaëlle G. (animatrice d'un centre de ressources numériques) crn-kleber@laligue13.fr
- Stéphanie R. (assistant projet biliothèque, agence régionale du Livre PACA) stephanie.rosso@livre-paca.org
- François B. (Fablab Manager) françois@e-in.fr
- Marine G. (médiateur numérique EPN Martigues) marine.guillemin@ville-martigues.fr
- David M. (médiateur numérique EPN Martigues) david.morin@ville-martigues.fr
- Chahreddine S. (médiateur numérique Evaléco Grasse) charly@evaleco.org


**mots clés :** quantifiable, catégorisation et agrégation/cumul des données, récolter, conserver pour une pérennité


"*Poor  numbers*" statistique de developpement en Afrique
Stat contenant de nombreuses erreurs
(calcul du PIB basé sur des enquêtes ; écarts importants selon l'institut)

Définition des données peut se baser en médiation sur le schéma :
Data->Information->Knowoledge->Visdom pyramide (avec Data comme base)
Soit Données->Informations->Connaissances->Sagesse

info "la France est en récession", à partir d'une courbe, la visualition sera necessaire, notamment pour l'analyse
présenter les données et forcément passer par une phase de visualisation (intelligible)
pyramide interessante pour définir la données pendant des actions de médiation
plus que des tableurs : graph..
pyramide est aussi criticable, est important de la remettre en question; tous les philosophes/ scientifiques passent par la données pour établir des théories ?
Les données s'adressent aux machines

the data revolution coeur des infrastructure de données




---
---

# Jour 2

Crowdsourcing--> https://github.com/datactivist/formation_crowdsourcing_poitiers
https://www.mapillary.com
--> version réduite : https://docs.google.com/presentation/d/1RcFECCyv7UOTRqbffWt7wcSexprOM45imU_FZn0UM-M/edit#slide=id.p
(formation : http://opendata.maregionsud.fr/fileadmin/user_upload/tx_ausynews/ODL/ODL_OpenRefine_Marseille_2017-06-09-v2.pdf)
https://github.com/datactivist/panorama_dataviz
https://lisacharlotterost.github.io/
https://source.opennews.org/articles/what-i-learned-recreating-one-chart-using-24-tools/

---

# Méthodologie
Pipeline : https://datactivist.coop/datamythes/

## 1 - Définir
- Définir précisement le problème
- Identifier les données utiles

## 2 - Trouver : des données
Recherche dans google avec la mention :
```javascript=
//Limiter les recherches aux fichiers .csv
filetype:csv

//Limiter la recherche sur un seul site défini
site:gouv.fr

//Exemple de requête google :
"metropole filetype:csv site:opendatafrance.net"
```

Google dataset Search : cherche que des bases de données

Site permettant de récupérer des données :
- data.gouv.fr
- data.opendatasoft.com

## 3 - Récupérer
- Téléchargement direct
- API ou web service
- Scrapping de données
- Copier / coller
- Extraction (OpenStreetMap)

## 4 - Vérifier
- Bon sens
- Demander a la source
- Communauté d’experts
- Statistiques

## 5 - Nettoyer
Préparer les données pour les analyser
- Toilettage
- Edition
- Consolidation
- Erreurs fréquentes
- Format pour les dates, les doublons, les fautes d’orthographe

Curation de données :
- https://teamopendata.org/t/curation-de-donnees-data-is-plural/734
- https://tabula.technology/
- https://dive.media.mit.edu/

Open Refine : http://openrefine.org/
Quartz bad data guide : https://github.com/Quartz/bad-data-guide
Sprint qualité : https://infolabs.io/sprint-qualite

## 6 - Analyser
Type d’analyse :
- Analyse statistique
- Analyse spatiale

Outils d'aide à l'analyse :
- Tableur
- R
- QGIS (données géo)
- Etc.

## 7 - Présenter
Savoir ce qu’on essaye de montrer

Outils permettant de présenter les données en graphique
- datavizcatalogue.com
- datavizproject.com

---

# Graphique des compétences maîtrisées

## Narrateur :
1. je sais aborder le sujet sous un angle intéressant
2. je suis capable de simplifier des idées complexes
3. J’ai de l’aisance à l’oral

## Analyste
1. je sais faire des calculs statistiques simples avec un tableau
2. J’ai de l’expérience avec les corrélations et leurs limites
3. J’ai beaucoup d’expérience en statistiques : les données ne me font pas peur

## Explorateur
1. Je saurais trouver une information rapidement sur le sujet de l’exploration
2. Je sais utiliser les opérateurs de recherche dans Google (file type, etc.)
3. Je sais lire les fichiers structuré type csv, json

## Designer
1. Je sais dessiner des schémas et des diagrammes
2. J’ai de l’expérience dans le design et l’infographie
3. J’ai déjà touché des outils de visualisation dynamique (D3…)

## Développeur / Technicien de données
1. Je sais manipuler des outils de nettoyage de données
2. Je sais utiliser des API pour récupérer des données
3. J’ai beaucoup d’expérience en développement je sais surmonter les difficultés techniques

---

# Aide pour l'atelier
Il est possible d'utiliser pour mener à bien notre atelier :
- On chart nine tools revisited (De lisecharlotterost)

---

# Open Food Fact

Site : https://fr.openfoodfacts.org

## Méthodologie de recherche
- Recherche simple
- - En utilisant le nom du produit
- - Récupérer la/les catégorie(s) du produit
- Recherche avancée
- - Utiliser le critère "catégorie" avec la catégorie du produit récupérée
- - Possibilité d'utiliser un autre critère
- - Choisir les options voulues (Ingrédients, nutriments, etc.)

## Affichage d'un graphique
Au lieu d'avoir une liste de produit sans aucun détails, il est possible de comparer les produits sur 2 éléments au choix et d'afficher la liste sous forme de graphique :
- Utiliser le critère "catégorie" avec la catégorie du produit récupérée
- Possibilité d'utiliser un autre critère
- Choisir les options voulues (Ingrédients, nutriments, etc.)
- Sélectionner l'élément à ordonner sur l'axe X (ex : sel)
- Sélectionner l'élément à ordonner sur l'axe Y (ex : matières grasses / Lipides)

## Fiche produit


---

# OSM et Overpass turbo
Overpass turbo est un outil internet d'exploration de données pour OpenStreetMap.
- OSM : https://www.openstreetmap.org
- Overpass Turbo : http://overpass-turbo.eu/
- Liste des différents éléments cartographiques : https://wiki.openstreetmap.org/wiki/FR:%C3%89l%C3%A9ments_cartographiques
- Atelier OSM : https://datactivist.coop/atelier-osm/

Imprimer le morceau de la carte voulu pour la compléter sur papier avant de reporter les différentes informations sur OSM : http://fieldpapers.org/


## Exemple de code
```jsonld=
/*
Génération d'un code permettant d'afficher différents éléments à plusieurs lieux différents
*/
//Si la requête est trop longue, augmentez le timeout
[out:json][timeout:120];
//Première méthode de délimitation des zones par ville
{{geocodeArea:Angers}}->.zoneVille1;
{{geocodeArea:Auxerre}}->.zoneVille2;
{{geocodeArea:Aix-en-Provence}}->.zoneVille3;
(
    //Deuxième méthode de délimitation des zones par régions ou autre
    area["name"="Bourgogne"]->.zoneRegion1;
    area["name"="Corse"]->.zoneRegion2;
    
    //Affichage des boulangeries sur zoneVille1
    node["shop"="bakery"] (area.zoneVille1);
    way["shop"="bakery"] (area.zoneVille1);
    relation["shop"="bakery"] (area.zoneVille1);
    
    //Affichage des pistes cyclages sur zoneVille2
    node["highway"="cycleway"] (area.zoneVille2);
    way["highway"="cycleway"] (area.zoneVille2);
    relation["highway"="cycleway"] (area.zoneVille2);
    
    //Affichage des distributeurs sur zoneVille3
    node["amenity"="vending_machine"] (area.zoneVille3);
    way["amenity"="vending_machine"] (area.zoneVille3);
    relation["amenity"="vending_machine"] (area.zoneVille3);
    
    //Affichage des aéroport sur zoneRegion1
    node["aeroway"="aerodrome"] (area.zoneRegion1);
    way["aeroway"="aerodrome"] (area.zoneRegion1);
    relation["aeroway"="aerodrome"] (area.zoneRegion1);
    
    //Affichage du réseau électrique sur zoneRegion2
    node["power"] (area.zoneRegion2);
    way["power"] (area.zoneRegion2);
    relation["power"] (area.zoneRegion2);
);
// Affiche le résultat
out body;
>;
out skel qt;
```

---
# Notes 

## Quelques définitions à retenir

**Une donnée**: est une représentation d'une information sous une forme brute destinée à faciliter son traitement 

**Une information**: est l'interprétation d'une source de données et n'est pas réutilisable de manière automatisée

**L'OPEN DATA**: consiste à mettre à disposition de tous, les données publiques ayant vocation à être librement accessibles et gratuitement réutilisables et ceci sous leur forme brute.


# Jour 3 : conception des ateliers de médiation

## Définir : trouver un angle

### Groupe 1 : pollution de l'air

2 pistes d'angles :
La pollution prend-elle des vacances ? (Corrélation entre les vacances scolaires et la pollution)
A quelle heure aérer pour éviter la pollution ? (suivre Trame A)


Question à garder en tête : à qui vous souhaitez vous adresser et combien de temps ?
2h difficile il sera difficile de faire plus que chercher les données.
Public : une classe de lycée
outils : atmosud, datasud, WTF CSV, public tableau, raw graph et educnet

### Groupe 2 (OFF) : Mobilité ; transports

Angle : Les transports en communs dans le pays d'Aix sont-ils suffisants et de qualité ? 
Durée de l'atelier : 2 à 3h
Public : usagers de bibliothèques (BIbliothèque Méjanes ?)

### Groupe 3 (OFF) : comment utiliser les données pour manger mieux et à moindre prix ? 
Atelier destiné à un double public : grand public (plutôt agé) en centre social en découverte du numérique et des collégiens/lycéens qui développent leur compétences numériques

Durée de l'atelier : 
- grand public: 2 ateliers de 2h
- collégiens/lycéens : 2h

Commencer par vidéo de présentation d'OpenFoodFacts dans Envoyé Spécial : https://www.youtube.com/watch?v=Tu9RA82-AwQ

## Trouver les données

### Groupe 1 : la pollution prend-elle des vacances ?

Définitions data & information

Base de données en Open Data définition

Visite de 2 sites avec des présentations :

•	https://www.atmosud.org/ 
Mots clés : atmosud 
•	https://www.datasud.fr/ 
Mots Clés : data sud

**Trame A**

Quel(s) capteur(s) ATMOSUD sont dans notre zone ? 
https://www.atmosud.org/
Il faut aller dans *Détail sur les données mesurées* à droite de la carte, on arrive sur : https://www.atmosud.org/donnees/acces-par-station
Exemple Grasse : Ozone
On va ensuite sur DATASUD
2 moyens de trouver le bon jeu de données sur data sud.fr :
-	En cherchant pollution dans la barre de recherche
-	Au préalable on a visité atmosud, donc en allant dans l’onglet Trouvés des Données/Organisations puis Atmosud
On a essayé plusieurs jeux de données en les ouvrants pour voir la forme des datas, on a fini par trouvé le bon :
https://trouver.datasud.fr/dataset/concentrations-horaires-de-polluants-dans-lair-ambiant-issues-du-reseau-permanent-de-mesures-automa

Pour Grasse : Mesures horaires de l’ozone

On télécharge le fichier au format CSV. On obtient un fichier nommé « ows », on le renomme *Mesures horaires d'ozone (O3)* et on ajoute l’extension .csv.


**Trame B**

**Eléments quotidiens concernant la pollution à l’échelle des villes**

Le public doit essayer de trouver quel sera le bon format de data : périodicité, espace géographique etc.
On cherche une base avec un ou des éléments quotidiens concernant la pollution à l’échelle des villes où des agglomérations, ainsi on peut comparer les périodes pertinemmentes. 
2 moyens de trouver le bon jeu de données sur [data sud.fr](https://www.datasud.fr) :
-	En cherchant pollution dans la barre de recherche
-	Au préalable on a visité atmosud, donc en allant dans l’onglet *Trouvés des Données/Organisations* puis *Atmosud*

On a essayé plusieurs jeux de données en les ouvrants pour voir la forme des datas, on a fini par trouvé le bon : *Indice de qualité de l'air des principales agglomérations de la région Sud*

https://trouver.datasud.fr/dataset/indices-de-qualite-de-l-air-des-principales-agglomerations-de-la-region-sud-pour-un-an-glissant-et-j

On télécharge le fichier au format CSV. On obtient un fichier nommé « ows », on le renomme *Indice de qualité de l'air des principales agglomérations de la région Sud* et on ajoute l’extension .csv.

**Trames A & B**

**Dates des périodes des vacances**

Il faut également récupérer les dates des périodes des vacances scolaires de l’année dernière et de l’année en cours, pour nous :
Mars 2018 à Mars 2019
Il faut le calendrier des vacances scolaires 2017-2018 et 2018-2019 en zone B :
https://vacances-scolaires.education/annee-2017-2018.php
https://www.service-public.fr/particuliers/vosdroits/F31952



### Groupe 2 : les transports en commun dans le Pays d'Aix sont-ils suffisants et de qualité ? 

Piste pour introduire l'atelier : https://www.planetoscope.com/transport/Mobilite
https://www.tictactrip.eu/

Des recherches sur transportdata.gouv.fr et datasud (LER, TER...)
Nous avons été alartés sur le rique d'une approche trop "technique".

L'angle initial portait sur la région. Vu l'étendu des données et le public cible (tout public) l'aire géographique a été réduite et plus précise (les réseaux du pays d'Aix). L'atelier pourra être reproductible pour d'autres réseaux ou à d'autres échelles par la suite.


Source des données trouvées : https://www.lepilote.com/fr/open-data/83

On sélectionne uniquement les réseaux Aix en Bus et Pays Aix Mobilités qui desservent l'intérieur du Pays d'Aix. 
Nous vérifions que les autres réseaux ne desservent pas l'intérieur du Pays d'Aix. Il y a juste à notre connaissance la ligne Aix TGV qui est un cas à part. 

dans opendatasoft : 
Nous téléchargeons les fichiers et les données IRIS pour la population (il risque d'y avoir des doublons). 
Nous vérifions les exports et les données stops et routes. 
Lecture en parralèle de la documentation http://doc.digitaltransport.io/data-transport-mali-GTFS/ pour comprendre l'organisation d'un fichier GTFS. Un appel est passé à l'auteur du support. 

Sources pour le téléchargement des itinéraires des bus : https://www.lepilote.com 
(onglet "accès pro" puis "Open Data")
Sélection des fichiers : Aix en bus et CPA en GTFS (General Transit Feed Specification) "également connu sous le nom de GTFS statique ou de flux statique pour le différencier de l'extension GTFS-realtime, définit un format de fichier commun pour les horaires de transports en commun et les informations géographiques associées. Les "flux" GTFS permettent aux agences publiques de publier leurs informations de transports en commun et aux développeurs de créer des applications qui utilisent ces données de manière interopérable.""
Le fichier "shape" représentant l'itinéraire entre deux points n'est pas toujours disponible.



Deuxième fichier de données utilisé : "population française par code IRIS 2012" à partir d'OpenData Soft
Précision IRIS : Ilôts regroupés pour l'info statistique ; entre 1 800 et 5 000 habitants

Sur OpenData Soft
Zones de chaleur pour afficher les zones d'arrêt et délimitation en noir pour les IRIS
Outil : Data France.info ?
réglage "coroplate"
Test : monochrome

Visualisation dans OSM
Autre outil de visualisaiton possible : overpass turbo

Recherche des des mots clés en lien avec les trasnports en communs dans Open Street Map
https://wiki.openstreetmap.org/wiki/FR:Éléments_cartographiques
Dans le sommaire sélection du thème "1.21 transports publics" https://wiki.openstreetmap.org/wiki/FR:Éléments_cartographiques#Transports_publics_.28public_transport.29
test "route = *" pour afficher tous les éléments.
utilsiation de highway = bus stop

Premiers constats : Le nombre d'arrêts sont concentrés dans la ville centre. De nombreux arrêt sont également visibles à Purycard, semblant importants compte tenu du nombre d'habitants (5000 habitants).

Questionnement de tester raw graph pour comparer l'affichage : https://rawgraphs.io
ou format dans datavizproject

Il est intéressant d'ajouter l'IRIS population.

Autres site consulté : https://datafrance.info/aix-en-provence-13290

https://datactivist.opendatasoft.com/explore/?sort=modified

Tableau ? non

Pistes pour des ateliers complémentaires à la suite de celui-ci : chercher à améliorer la visibilité des emplois par IRIS.

### Groupe 3 : comment utiliser les données pour mieux manger et moins cher ?


Atelier à destination des lycéens (2 heures) ou tous publics (2x2 heures);

Deux axes de questionnement : mieux manger, et moins cher. 
* Mieux manger : on se base sur l'indicateur NOVA de OFF qui prend surtout en compte le nombre de produits -notamment transformé. Pour l'instant cet indicateur peut correspondre au nombre d'ingrédient par aliments. On peut aussi prendre en compte le taux de sucre, de matière grasse et le nombre d'additifs.Tous ces critères sont pris en compte par l'indicateur NOVA

Si le groupe a le temps, on peut aller sur https://combiendesucres.fr/ et/ou https://cestemballepresdechezvous.fr/ pour les faire débattre sur ce qui est important pour eux dans le "bien manger".

* Moins cher : on se base sur le prix des produits. Pour débattre de ce que le prix d'un produit signifie on peut aller sur https://lamarqueduconsommateur.com/ . 

Choix de la catégorie de produits : bien faire gaffe aux mots clés sur OFF ( https://fr.openfoodfacts.org)  . Exemple de catégorie de produits et de critères faciles à appliquer : 
* Bouillons de cubes (nombres d'ingrédients ; sucres ; graisses)
* Compotes de fruits (nombres d'ingrédients ; sucres)
* Cacao en poudre (nombres d'ingrédients ; sucres)
* Céréales pour petits déjeuner (sucres; graisses; additifs)

Vidéo d'envoyé spécial de 5 minutes pour expliquer OFF spécial https://www.youtube.com/watch?v=Tu9RA82-AwQ

Site pour comparer les prix : http://www.prixing.fr/ ou drive (moins de produits mais permet de classer par prix)


## Récupérer


### Groupe 1 

Voir la section ## Trouver les données

### Groupe 2

Voir documentation : http://doc.digitaltransport.io/data-transport-mali-GTFS/

### Groupe 3

## Vérifier

### Groupe 1 

**Source :** atmosud, à priori une source fiable mais il faut vérifier les données avec WTFCSV

**Trame A**

On vérifie l'amplitude des chiffres, leurs régularités et leurs logiques en ouvrant le fichier CSV avec Libre office (pour ouvrir correctement choisir *jeu de caractère : Unicode (UTF-8)*)

On enregistre sous le fichier en format xlsx (Excel) pour pouvoir l'utiliser sous le logiciel Tableau public.

**Trame B**
On supprime les lignes inutiles, par exemple on veut garder Grasse


Sélectionner les villes qui ne nous intéressent pas et supprimer / supprimer les lignes entières. Enregistrer le fichier sous, ex : Indice quotidien des principales agglomérations Grasse
Il doit rester 364 jours (365 lignes)

Reprendre ce fichier et supprimer les périodes hors vacances et enregistrer sous pour avoir un autre fichier par exemple : Indice quotidien des principales agglomérations Grasse Vacances
Il doit rester 122 jours (123 lignes)

On va sur WTF CSV et on upload les 2 fichiers dans des  onglets différents :
https://www.databasic.io/en/wtfcsv/

**Résultats pour Grasse :** Visuellement on se rend compte que pendant les vacances, donc pour 122 jours soit un tiers de l’année  il y a 27 jours avec une qualité d’air médiocre sur 42 jours médiocres par an soit plus de la moitié. On voit immédiatement qu’il y a une surreprésentation des jours avec une qualité d’air médiocre pendant les vacances scolaires.


### Groupe 2

### Groupe 3


## Nettoyer

### Groupe 1 :
 On a nettoyé les données du tableau en enlevant les éléments inutils pour notre analyse.

### Groupe 2

### Groupe 3


## Analyser

### Groupe 1 

**Trame A**

Pour effectuer une data visualisation:
--> Ouverture du tableur (format excel) avec "tableau public"
On a effectué les réglages de la colonnes "date début" en "dates et heures". 
Dans "feuille 1", nous avons mis dans colonne: 3 fois le champs "date_debut" (année/mois/jour)
Dans "mesures" (en bas à gauche) sélectionner "valeurs", une fois sélectionné, sélectionner le modèle en haut à droite. 
Nous avons mis dans ligne: le champs "date_début" réglé sur heure. 
Pour visualiser les données, on peut enlever le "jour" pour visualier par mois. 

**Trame B**

Pour affiner nos résultats il faut faire des datas visualisations avec les dates journalières visibles toute en étant lisibles !
On va sur RAW GRAPH ou un autre site pour faire de la data visualisation :
http://app.rawgraphs.io/
Pour Raw Graph : dans 2 onglets on copie colle les lignes de données en format brut (séparés par des virgules)
On laisse les gens essayer différentes formes de représentations

### Groupe 2

### Groupe 3

## Présenter

### Groupe 1 

### Groupe 2

### Groupe 3
