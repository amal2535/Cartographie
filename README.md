# Cartographie en R

Mon objectif est de faire projeter des statistiques:"l'évolution du nombre des cliniques et leurs capacités entre 2014 et 2018 en Tunisie" sur une carte géorgraphie.

On a besoin de la:

**Construction d’un jeu de données avec une référence spatiale
**Importation d’un fond de carte
**Liaison entre les données et les fonds de carte
**Affichage des données
**Ajout d’un habillage

Nous allons utiliser les packages

"maptools" qui permet de manipuler et représenter des données spatiales
"classInt" qui permet de discrétiser des séries quantitatives continues
"RColorBrewer" qui permet de choisir des gammes de couleur

Pour le fond de la carte il faut avoir les fichiers

un fichier “.shp” stockant les géométries des entités
un fichier “.bdf” stockant la table attributaire
un fichier “.shx” stockant l’index de la géométrie des entités
un fichier “.prj” qui précise le système de projection utilisé.
Ces fichiers existent dans le dossier"source"
