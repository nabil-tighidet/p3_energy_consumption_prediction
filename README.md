# Projet de Prédiction des Émissions de CO2 et de Consommation d'Énergie pour les Bâtiments Non Résidentiels de Seattle

![Seattle Logo](seattle.jpg) <!-- Replace link_to_logo.png with the actual logo image of Seattle -->

## Description du Projet

Bienvenue dans le repository GitHub du projet (fictif) pour la ville de Seattle ! Afin de contribuer à atteindre l'objectif de ville neutre en émissions de carbone d'ici 2050, on se concentre sur la consommation et les émissions des bâtiments non destinés à l'habitation. L'objectif est de prédire les émissions de CO2 et la consommation totale d'énergie de ces bâtiments, pour ceux qui n'ont pas encore été mesurées, en utilisant des données structurelles des bâtiments, telles que la taille, l'usage, la date de construction, la situation géographique, etc..

## Les Données

Des relevés minutieux ont été effectués par les agents de la ville en 2016. Cependant, ces relevés sont coûteux à obtenir, nous souhaitons donc exploiter ceux déjà réalisés pour tenter de prédire les émissions de CO2 et la consommation d'énergie des bâtiments non résidentiels pour lesquels elles n'ont pas encore été mesurées. Elles sont disponibles [ici](https://data.seattle.gov/dataset/2016-Building-Energy-Benchmarking/2bpz-gwpy)

## Objectifs de la Mission

La mission se résume comme suit :

1. Réaliser une courte analyse exploratoire pour comprendre les données et identifier des informations pertinentes.

2. Tester différents modèles de prédiction pour répondre au mieux à la problématique.

3. Évaluer l'intérêt de l'"ENERGY STAR Score" pour la prédiction d'émissions et l'intégrer dans la modélisation.

Voici quelques instructions supplémentaires pour mener à bien la mission :

- Nous devons nous passer des relevés de consommation annuels futurs pour éviter la fuite de données.
- Rien ne nous interdit de déduire des variables structurelles aux bâtiments à partir des relevés existants, comme la nature et les proportions des sources d'énergie utilisées.
- Nous devons accorder une attention particulière au traitement des différentes variables en trouvant de nouvelles informations utiles et en optimisant les performances en appliquant des transformations simples (normalisation, passage au log, etc.).
- Il est essentiel de mettre en place une évaluation rigoureuse des performances de la régression et d'optimiser les hyperparamètres et le choix d'algorithmes de Machine Learning à l'aide d'une validation croisée.
