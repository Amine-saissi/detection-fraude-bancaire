# Détection de fraude bancaire avec Machine Learning

## 📌 Présentation

Ce projet consiste à développer un modèle de Machine Learning capable de détecter des transactions bancaires frauduleuses.

L'objectif est de comparer plusieurs modèles de classification et d'évaluer leur capacité à identifier les transactions frauduleuses dans un dataset fortement déséquilibré.

## 🎯 Objectifs

- Explorer et comprendre les données
- Identifier le déséquilibre entre les transactions normales et frauduleuses
- Préparer les données pour le Machine Learning
- Comparer plusieurs modèles de classification
- Évaluer les performances avec la précision, le rappel et le score F1
- Analyser les matrices de confusion

## 📊 Dataset

Le projet utilise le dataset **Credit Card Fraud Detection** disponible sur Kaggle.

Le dataset contient :

- 284 807 transactions
- 492 transactions frauduleuses
- 31 variables
- Une variable cible `Class`
  - `0` : transaction normale
  - `1` : transaction frauduleuse

Le dataset est fortement déséquilibré : les transactions frauduleuses représentent une très faible partie des transactions.

## 🛠️ Technologies utilisées

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

## 🔎 Étapes du projet

### 1. Exploration des données

Analyse de la structure du dataset, des types de variables et recherche de valeurs manquantes.

### 2. Préparation des données

- Séparation des variables explicatives et de la variable cible
- Séparation des données en ensembles d'entraînement et de test
- Standardisation de certaines variables
- Prise en compte du déséquilibre des classes

### 3. Modélisation

Plusieurs modèles de classification ont été testés :

- Régression logistique
- Régression logistique avec gestion du déséquilibre des classes
- Random Forest avec gestion du déséquilibre des classes

### 4. Évaluation

Les modèles sont évalués avec :

- Precision
- Recall
- F1-score
- Matrice de confusion

## 📈 Résultats

Les performances des différents modèles sont comparées dans le notebook afin d'identifier le modèle le plus adapté à la détection des fraudes.

Dans ce contexte, le **Recall** et le **F1-score** sont particulièrement importants car une fraude non détectée peut être problématique.

## 📁 Contenu du repository

```text
detection-fraude-bancaire/
│
├── detection_fraude_bancaire.ipynb
└── README.md
