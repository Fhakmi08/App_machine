# 🩺 Projet de Classification Binaire - Prédiction Médicale (Diabète)

Ce projet a pour objectif de prédire l'apparition d'une maladie (comme le diabète) à partir de données médicales en utilisant des **méthodes de Machine Learning**. Il est basé sur une **analyse exploratoire**, la préparation des données et l'entraînement de plusieurs modèles de classification.

## 📁 Contenu du projet

- `Untitled3.ipynb` : Notebook principal contenant toutes les étapes du projet
- `README.md` : Fichier de documentation (vous êtes ici)

## 🧪 Objectif du projet

Utiliser des algorithmes de machine learning pour prédire si un patient est atteint de la maladie (`Outcome = 1`) ou non (`Outcome = 0`), à partir de caractéristiques comme le taux de glucose, la pression artérielle, l'IMC, etc.

## 🗃️ Dataset utilisé

Le jeu de données est probablement inspiré du **Pima Indians Diabetes Dataset**, avec les variables suivantes :
- `Pregnancies`
- `Glucose`
- `BloodPressure`
- `SkinThickness`
- `Insulin`
- `BMI`
- `DiabetesPedigreeFunction`
- `Age`
- `Outcome` (variable cible)

## ⚙️ Étapes du pipeline

### 1. Chargement et préparation des données
- Nettoyage des valeurs manquantes
- Normalisation ou standardisation

### 2. Analyse exploratoire
- Visualisations : histogrammes, boxplots, heatmaps
- Étude de la répartition de la variable cible (`Outcome`)
- Détection de corrélations (ex : `Glucose` fortement corrélé à `Outcome`)

### 3. Entraînement de modèles
- Séparation des données en train/test
- Modèles testés : Logistic Regression, Decision Tree, KNN, etc.
- Évaluation avec les métriques : **accuracy**, **f1-score**, **matrice de confusion**

### 4. Recommandations d’amélioration
- Utiliser **SMOTE** ou autre technique d’équilibrage pour les classes
- Ajouter une **validation croisée (cross-validation)** pour fiabiliser les scores
- Tester des modèles plus avancés comme **XGBoost**, **Random Forest**, ou **réseaux de neurones**

## 🧠 Résultats clés

- Bonnes performances du modèle de régression logistique (baseline)
- Les classes sont déséquilibrées : environ 65% de "0" et 35% de "1"
- La variable `Glucose` est un indicateur fort du diabète

## 🛠️ Technologies utilisées

- Python 3.x
- Bibliothèques : `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- Jupyter Notebook

## 📈 Exemples de visualisations

- Histogrammes des variables
- Répartition des classes
- Heatmap des corrélations
- Matrices de confusion

## 🔁 À améliorer dans de futures versions

- Implémenter une pipeline automatisée avec `Pipeline` de scikit-learn
- Sauvegarde des modèles avec `joblib` ou `pickle`
- Intégrer un dashboard pour visualiser les prédictions

## 📌 Auteurs

- Réalisé par : [Votre nom ici]
- Contact : [Votre email ou profil GitHub]

## 🧾 Licence

Projet éducatif – Usage académique ou personnel uniquement.
