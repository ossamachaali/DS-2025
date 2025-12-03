# Compte-rendu des fichiers 

## Description générale
Les fichiers contiennent un projet d'analyse et de classification du jeu de données Iris, un classique en machine learning. Le fichier `.py` est un script Python, tandis que le `.ipynb` est un notebook Jupyter interactif exécuté sur Google Colab. Le projet comprend l'exploration des données, diverses visualisations et la mise en œuvre de plusieurs modèles de classification.

## Bibliothèques utilisées
- `pandas` pour la manipulation des données tabulaires.
- `matplotlib.pyplot` et `seaborn` pour la visualisation des données.
- `sklearn` pour la préparation, le découpage des données, les modèles (SVM, régression logistique, KNN, arbre de décision) et l'évaluation.

## Traitement des données
- Téléchargement du dataset Iris via l’API Kaggle.
- Chargement en DataFrame pandas.
- Inspection générale (dimensions, types, valeurs manquantes).
- Analyse des colonnes dont la cible "Species" comprenant trois classes.
- Vérification de l’absence de valeurs nulles, assurant la qualité des données.

## Visualisations
- Graphiques de dispersion (scatter plots) des mesures de sépales et pétales par espèce.
- Histogrammes des variables.
- Graphiques en violon pour la répartition des mesures par espèce.
- Modèles simples de régression linéaire pour observer la relation entre longueur et largeur des sépales.

## Modélisations machine learning
- Division en ensembles d’entraînement (70 %) et de test (30 %).
- Sélection des variables caractéristiques (longueur et largeur de sépales et pétales).
- Entraînement avec plusieurs algorithmes : SVM, régression logistique, arbre de décision, KNN.
- Évaluation de la précision (accuracy) des modèles sur les ensembles d’apprentissage et de test.
- Comparaison pour détecter surapprentissage ou sous-apprentissage.
- Étude parallèle des performances des modèles selon l’utilisation uniquement des caractéristiques des sépales ou des pétales.

---

Ce compte-rendu synthétise l’analyse, la visualisation et la modélisation supervisée réalisées sur le dataset Iris dans les fichiers fournis.

