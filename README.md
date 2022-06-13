# Datavalanches-VS

# 1. Description

Cette visualisation de données tente de visualiser un set de données comptabilisant les accidents mortels causés par des avalanches en Suisse depuis l'hiver 1995/96. 
Mis à diposition par _l'Institut pour l'étude de la neige et des avalanches_ sur son site (https://www.slf.ch/fr/index.html), ce set de données en format .csv est extrêmement riche et complet.

<img width="1422" alt="Capture d’écran 2022-06-13 à 12 52 03" src="https://user-images.githubusercontent.com/100225833/173338507-572d1b69-5d79-4a1e-9663-4d09177d0cef.png">


L'objectif du projet est de visualiser un graphique en "connected scatter plot" pour le canton du Valais, permettant de mettre en rapport les années hydrologiques et le nombre de morts par année dans le canton. 

<img width="1076" alt="Capture d’écran 2022-06-13 à 12 39 36" src="https://user-images.githubusercontent.com/100225833/173336435-e475ffcf-3e34-44b8-be0c-0e854c6599f0.png">

=> _Outil_

Ce projet utilise principalement la librairie D3 de javascript.

=> _Données_

Chaque entrée du jeu de données correspond à une avalanches ayant fait des victimes. Celles-ci sont décrites par plusieurs catégories: 
- le numéro d'identification de l'avalanches, 
- la /date/, 
- la qualité de la date, 
- l'année hydrologique (de 1995/96 à 2020/21), 
- le canton, 
- le lieu-dit, 
- les coordonnées de la zone de départ de l'avalanche en X et Y,
- la qualité de ces coordonnées
- l'altitude de la zone de départ de l'avalanche
- l'orientation de la pente
- le degré d'inclinaison de la pente
- le danger d'avalanche annoncé ce jour-là
- le nombre de victimes
- le nombre de personnes emportées dans l'avalanche
- le nombre de personnes complètement enneigées par l'avalanche
- l'activité des victimes (hors-piste, ski de randonnée, traversée de couloir, dans un bâtiment, autres/mix/inconnu)

# 2. Procédure d'installation

Pour visualiser ce projet, il faut le faire tourner localement.
Il s'agit donc de télécharger le zip et de l'extraire dans un dossier. Ce dossier est à ajouter dans un éditeur de code du type _Visual Studio Code_  et en utilisant une extension comme _LiveServer_, cela permet de visualiser le projet de manière locale sur un navigateur. 

# 3. Contexte de développement

Ce projet a été développé par Baptiste Ruedin dans le cadre du cours _Visualisation de données_ dispensé par Isaac Pante (SLI, Lettres, UNIL)) durant le semestre de Printemps 2022.



