![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) 
![Power Query](https://img.shields.io/badge/Power_Query-217346?style=for-the-badge) 
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge) 
![SQL](https://img.shields.io/badge/SQL-00758F?style=for-the-badge&logo=mysql&logoColor=white) 

# Sales Performance & Competitor Analysis 

## Objectif 

Analyse des ventes de plusieurs fabricants d'articles de sport afin d'évaluer leurs performances commerciales et de les comparer à celles de leurs concurrents. 

Ce projet couvre l'ensemble de la chaîne décisionnelle (Business Intelligence) : 

- Préparation des données. 
- Modélisation dimensionnelle. 
- Création de mesures DAX. 
- Conception d'un tableau de bord interactif. 

## Sources de données  

Les données proviennent de plusieurs fichiers CSV contenant les ventes, les informations sur les fabricants ainsi que les caractéristiques des produits. 

## Préparation des données (Power Query) 

Importation des données. 

- Nettoyage des données : gestion des doublons, des valeurs manquantes, fractionnement de colonnes, création de nouvelles colonnes, modification des types de données. 
- Transformation des données : pivot/unpivot, transposition, jointures et fusion des tables. 

## Modélisation 

- Création d'une table de dates. 
- Gestion des relations entre les tables. 
- Construction d'un modèle de données en Snowflake Schema. 
- Mesures DAX 

<img width="941" height="609" alt="image" src="https://github.com/user-attachments/assets/9c1de037-aa95-4409-b11c-fcfe46d1b655" />

## Création de mesures métier telles que : 

- Chiffre d'affaires total. 
- Cumul des ventes (YTD). 
- Évolution par rapport à l'année précédente (SAMEPERIODLASTYEAR). 
- Fonctions Time Intelligence (YTD, MTD, QTD, YoY). 

## Dashboard 

Le tableau de bord est composé de deux pages. 

#### Page 1 – Analyse des performances 

<img width="1327" height="745" alt="image" src="https://github.com/user-attachments/assets/783d5586-0105-4ed8-88a3-ca3d1ffb043a" />


Elle permet notamment de répondre aux questions suivantes : 

- Quels fabricants génèrent le plus de chiffre d'affaires ? 
- Quels segments sont les plus performants ? 
- Quels produits présentent la plus forte croissance ? 
- Comment évoluent les ventes dans le temps ? 
- Quels pays offrent les meilleures performances ? 

#### Page 2 – Analyse avancée 

<img width="1315" height="727" alt="image" src="https://github.com/user-attachments/assets/f754927b-4b32-4e69-ade7-bd6b7dec4398" />


Cette page exploite les fonctionnalités d'IA de Power BI (Key Influencers et Decomposition Tree) afin d'identifier les principaux facteurs influençant les ventes et de faciliter l'analyse des causes (Root Cause Analysis). 

**Idriss FEKARI** 
