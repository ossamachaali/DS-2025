# Compte Rendu Détaillé : Analyse de la Performance des Étudiants

***

## Introduction

Ce notebook présente une analyse approfondie sur la performance des étudiants à partir d'un dataset Kaggle regroupant 1000 enregistrements avec 8 variables clés : genre, origine ethnique, niveau d'éducation des parents, type de repas, préparation aux tests, et scores aux examens (mathématiques, lecture, écriture). L'objectif est de comprendre les facteurs influençant la performance des étudiants et de modéliser les résultats à l'aide de régressions.

***

## Chargement des Données

Les données sont chargées depuis la plateforme Kaggle via différentes méthodes (kagglehub ou URL publique). Le dataset contient 1000 lignes et 8 colonnes principales. Un aperçu montre des caractéristiques variées dans les catégories démographiques et les résultats aux tests.

***

## Exploration Initiale des Données

- Le dataset comprend 5 variables catégorielles et 3 variables numériques (scores).
- Statistiques descriptives :
  - Moyenne Score Mathématiques : 66.09 (écart-type 15.16)
  - Moyenne Score Lecture : 69.17 (écart-type 14.60)
  - Moyenne Score Écriture : 68.05 (écart-type 15.19)
- Les colonnes sont listées et leur type vérifié.

***

## Nettoyage des Données

- Vérification et suppression des valeurs manquantes : aucune valeur manquante détectée.
- Vérification et suppression des doublons : aucun doublon détecté.
- Standardisation des noms de colonnes pour homogénéité.
- Création des variables dérivées :
  - `averagescore` : moyenne des scores en mathématiques, lecture, écriture.
  - `performancecategory` : classification binaire des performances (Pass si score moyen ≥ 50, Fail sinon).
- Détection des valeurs aberrantes dans les scores, conservées pour l'analyse.

***

## Visualisations

- Histogrammes des distributions des scores par matière et du score moyen.
- Visualisation des effets du suivi de préparation aux tests et du type de repas.
- Visualisation Régression Linéaire : prédictions vs valeurs réelles, analyse des résidus.
- Matrice de confusion pour la classification binaire Pass/Fail.

***

## Modèles de Machine Learning

### Régression Linéaire (Prédiction score de mathématiques)

