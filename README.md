<p align="center">
  <img src="logo_OCR.jpg" alt="Logo Academy" width="200">
</p>

<h1 style="text-align: center;">Projet d’analyse exploratoire</h1>

# Contexte

Je suis __Data Scientist__ au sein de la start-up *academy*, qui propose des contenus de formation en ligne pour un public allant du lycée à l’université.

Mon manager, Mark, m’a présenté le projet d’expansion internationale de l’entreprise. Il m’a confié une première mission d’analyse exploratoire : déterminer si les données éducatives de la Banque Mondiale peuvent aider à orienter les choix stratégiques d’implantation à l’étranger. [Voici le lien vers le jeu de données. ](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Donn%C3%A9es+%C3%A9ducatives/Projet+Python_Dataset_Edstats_csv.zip)

[(issu du site de la Banque Mondiale). ](https://datacatalog.worldbank.org/dataset/education-statistics)



🎯 __Mon objectif__ : identifier les pays présentant un fort potentiel pour les services proposés par academy, et anticiper l’évolution de ce potentiel dans le temps.

Je vais pour cela suivre un ensemble d’exercices guidés, qui me permettront de valider si ces jeux de données fournissent des insights pertinents pour appuyer la prise de décision.

Ce premier exercice consiste à explorer les jeux de données en surface, afin d’en dégager une première compréhension.

## Introduction

Ce projet a été réalisé dans le cadre d'une mission d'analyse exploratoire pour la start-up *academy*, qui propose des contenus de formation en ligne. L'objectif est d'explorer les données éducatives de la Banque Mondiale pour identifier les pays présentant un fort potentiel pour les services proposés par l'entreprise.

## Objectif

L'objectif principal est d'identifier les pays présentant un fort potentiel pour les services proposés par *academy* et d'anticiper l'évolution de ce potentiel dans le temps.

## Étapes de l'analyse

1. **Chargement des données** : Importation des bibliothèques nécessaires et chargement des fichiers CSV.  
2. **Visualisation des données** : Affichage des premières lignes et dimensions des jeux de données pour une première compréhension.  
3. **Nettoyage des données** : Première étape de nettoyage pour préparer les données à l'analyse.  
4. **Sélection des indicateurs pertinents** : Filtrage des indicateurs en lien avec l’éducation et les besoins d'academy.  
5. **Préparation des données pour l’analyse** : Mise en forme, gestion des valeurs manquantes et normalisation des données.  
6. **Analyse exploratoire** : Exploration statistique et visuelle des indicateurs pour repérer des tendances par pays.  
7. **Identification des pays à fort potentiel** : Croisement des données pour repérer les pays les plus prometteurs.


## Jeux de données utilisés

- `EdStatsCountry.csv` : 241 lignes, 32 colonnes
- `EdStatsSeries.csv` : 3665 lignes, 21 colonnes
- `EdStatsCountry-Series.csv` : 613 lignes, 4 colonnes
- `EdStatsFootNote.csv` : 643638 lignes, 5 colonnes
- `EdStatsData.csv` : 886930 lignes, 70 colonnes

## Instructions pour l'exécution

Pour reproduire l'analyse, exécutez le notebook `main.ipynb` en suivant les étapes décrites. Assurez-vous d'avoir les fichiers CSV dans le répertoire `Projet+Python_Dataset_Edstats_csv/` et d'avoir installé les bibliothèques nécessaires (pandas, numpy, matplotlib, seaborn). 

