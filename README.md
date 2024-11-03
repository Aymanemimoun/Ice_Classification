# Projet de Classification de la Quantité de Glace au Groenland
## Description

Ce projet vise à construire un modèle de classification pour prédire la quantité de glace (faible ou élevée) en un point donné au Groenland, 
en utilisant des enregistrements de signaux infrasonores et des variables climatiques. À partir de données fournies par le Centre Européen 
pour les Prévisions Météorologiques (ECMWF), nous avons utilisé des techniques d'apprentissage supervisé afin d'entraîner et comparer différents modèles de classification.

L’objectif est de déterminer si un niveau de glace élevé ou faible peut être prédit à partir des données environnementales en appliquant des algorithmes tels que la forêt aléatoire,
l'arbre de décision, et autres méthodes d'ensemble.

## Données

Le jeu de données comprend :

Variable cible : La quantité de glace, initialement continue, est transformée en une variable binaire (faible ou élevée) selon un seuil défini.
Variables explicatives : Variables climatiques telles que la température, la vitesse du vent, la concentration de glace de mer, et la décharge d'eau liquide 
sur plusieurs régions du Groenland.

Les données sont fournies dans les fichiers data_features.csv (variables explicatives) et data_Targets.csv (variable cible).
