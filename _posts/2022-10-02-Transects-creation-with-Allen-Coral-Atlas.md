---
layout: post
title: Transects creation with Allen Coral Atlas
date: '2022-10-02'
categories: Protocols
tags: Mapping
---
#Map mapping with Allen Coral Atlas, Mapshaper and R
##Allen Coral Atlas

### Conexion 
1. Entrer identifiant et mot de passe
2. Selectionner la zone sur laquelle vous voulez travailler 
3. Commencer

### Importer des fichiers
1. Cliquer sur l'onglet `My area` puis `Upload a GeoJSONor KML file`. Une fois `Upload a GeoJSONor KML file` selectionner, selectionner le fichier que vous souhaitez importer puis appuyer sur `transférer`. 
2. Une fois le fichier transferer sur le logiciel, une case **illustrer ci-dessous** s'affichera. Cliquer sur `Save area`, puis entrer le nom de la zone que vous voulez ajouter dans le logiciel puis appuyer sur `Save`. 

### Gerer les fichiers importer
1. Une fois les fichiers importer, nous souhaitons les faires apparaitre sur notre carte. Pour se faire, cliquer sur l'onglet `My area`. Une fenetre souvrira et vous permettra de choisir le fichier voulu. 
2. Plusieurs possibilités s'offre à vous, le premier logo constitué d'une **loupe avec des barplot à l'intérieur** vous permets de voir les stats de votre zone. Le deuxieme logo contistué d'une **feuille** vous permets de telecharger le fichier. Le troisème logo constitué d'un **carré** vous permets de faire afficher la zone. Enfin le dernier logo constitué d'une **poubelle** permets de suprimmer le fichier du logiciel. 

### Créer une nouvelle zone
1. Cliquer sur l'interfasse à gauche de l'écran **illustrer ci-dessous**
2. Cliquer sur le logo **carré** afin de créer la zone
3. Le logo régle permets de mesurer des distance sur la carte

*Une fois les fichiers importer ou créer*

### Modification du format de fichier
1. Télecharger le fichier en utilisant la fonction `Download area asset`(logo carré), accépter les condition puis cliquer sur `Prepare Download`. Un mail vous sera envoyer, attendez le deuxième mail comprenant le fichier voulu. 
2. Telecharger le ficheir en cliquant sur `Download Now`
3. Ouvrir le fichier telecharger puis accéder au fichier `boundary` puis renommer le fichier `XXX_boundary.geojson`. 
4. Ouvrir le logiciel [Mapshaper](https://mapshaper.org). 
5. Ajouter le fichier à *Mapshaper* puis selectionner `import`
6. Selectionner le bouton `Export`en haut à droite de l'interfasse puis selectionner `Shapefile` comme format voulu. enfin cliquer sur `Export`
7. Decompresser le fichier `.zip`et ouvrir le fichier et 
8. Importer l'integralité des fichiers dans votre fichier `Moorea_polygons`situer dans votre fichier `Data` se situant lui même dans `Ranalysis`
8. Le reste du travail se déroullera sur **Rstudio**

### R


 