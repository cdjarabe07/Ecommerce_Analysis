# Analyse E-Commerce — UCI Online Retail

## Objectif du projet

Ce projet a pour objectif d’analyser les données transactionnelles d’un site e-commerce afin de :

* Nettoyer des données réelles et imparfaites
* Calculer des indicateurs de performance (KPI)
* Identifier des insights business exploitables
* Comprendre le comportement des clients

---

## Dataset

* Source : UCI Online Retail
* Format : `.xlsx`
* Description : transactions d’une boutique en ligne basée au Royaume-Uni (~500 000 lignes)

---

## Technologies utilisées

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Instructions pour exécuter le projet

### 1. Cloner le dépôt GitHub

```
git clone https://github.com/cdjarabe07/Ecommerce_Analysis
cd Ecommerce_Analysis
```

---

### 2. Installer les dépendances

```
pip install pandas matplotlib openpyxl jupyter
```

---

### 3. Lancer Jupyter Notebook

```
jupyter notebook
```

---

### 4. Exécuter les notebooks dans l’ordre

1. `01_data_loading.ipynb`
2. `02_data_cleaning.ipynb`
3. `03_feature_engineering.ipynb`
4. `04_eda_analysis.ipynb`
5. `05_business_insights.ipynb`

---

## Préparation des données

* Échantillonnage de 10% du dataset
* Suppression des valeurs nulles
* Filtrage des quantités négatives (retours)
* Suppression des prix nuls
* Conversion des dates
* Création de la variable **Revenue**

---

## Analyses réalisées

### Analyse géographique

* Identification des pays générant le plus de revenus
* Forte concentration du chiffre d’affaires sur un seul marché

### Analyse produits

* Identification des produits les plus rentables

### Analyse clients

* Identification des clients à forte valeur

### Segmentation RFM

* Segmentation des clients selon :

  * Récence
  * Fréquence
  * Montant

### Analyse temporelle

* Évolution du chiffre d’affaires dans le temps
* Détection de saisonnalité

---

## Insights principaux

* Le Royaume-Uni domine largement les revenus
* Une minorité de clients génère une grande partie du chiffre d’affaires
* Certains produits concentrent la majorité des ventes
* Présence d’une saisonnalité dans les ventes
* Une grande partie des clients est peu engagée

---

## Recommandations

* Diversifier les marchés à l’international
* Mettre en place des stratégies de fidélisation
* Exploiter les périodes de forte demande
* Relancer les clients inactifs

---

## Structure du projet

```
Ecommerce_Analysis/
│
├── data/
│   └── Online_Retail.xlsx
│
├── notebooks/
│   ├── 01_data_loading.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_eda_analysis.ipynb
│   └── 05_business_insights.ipynb
│
├── outputs/
│   ├── cleaned_data.pkl
│   └── country_revenue.csv
│
├── visuals/
│   └── top_10_countries.png
│
└── README.md
```

---

## Lien du projet GitHub

`https://roadmap.sh/projects/ecommerce-data-analysis`

---
