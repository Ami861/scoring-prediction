# Projet de Scoring Crédit – Prédiction du Défaut de Paiement

## Contexte du projet

Les institutions financières doivent évaluer avec précision le risque de défaut de paiement avant d’accorder un crédit. Ce projet a pour objectif de développer un modèle de scoring crédit permettant de prédire la probabilité de défaut de paiement d’un client le mois suivant.

Le projet s’appuie sur le *Default of Credit Card Clients Dataset* (Taiwan, 2005), qui contient des informations démographiques, financières ainsi que l’historique de facturation et de paiement de clients détenteurs de cartes de crédit.

---

## Objectifs

* Analyser et comprendre le profil des clients à risque
* Identifier les variables clés influençant le défaut de paiement
* Construire et comparer plusieurs modèles de classification
* Évaluer les performances des modèles à l’aide de métriques adaptées
* Mettre en place un système de scoring exploitable dans un contexte métier

---

## Jeu de données

**Source :** Default of Credit Card Clients Dataset – Taiwan (2005)

### Description

Le jeu de données contient :

* Des informations démographiques (âge, sexe, niveau d’éducation, statut marital)
* Des informations financières (montant du crédit accordé)
* L’historique des retards de paiement sur plusieurs mois
* Les montants des factures et des paiements mensuels
* Une variable cible indiquant le défaut de paiement le mois suivant

Ces données sont utilisées pour construire un modèle de prédiction du risque de défaut.

---

## Méthodologie

### 1. Définition du problème et des exigences

* Compréhension du besoin métier et des enjeux du scoring crédit
* Analyse de l’existant
* Définition des indicateurs de performance (AUC, précision, F1-score, etc.)

### 2. Collecte et préparation des données

* Importation du jeu de données
* Nettoyage des données :

  * gestion des valeurs manquantes
  * traitement des valeurs aberrantes
  * correction des incohérences

### 3. Analyse exploratoire des données (EDA)

* Analyse des distributions des variables
* Visualisation des corrélations
* Identification des comportements à risque

### 4. Feature engineering et sélection des variables

* Création de nouvelles variables (ratios, agrégations, indicateurs comportementaux)
* Encodage des variables catégorielles
* Normalisation ou standardisation des variables numériques
* Sélection des variables pertinentes pour la modélisation

### 5. Modélisation

* Séparation du jeu de données en ensembles d’entraînement et de test
* Entraînement de plusieurs modèles de classification :

  * régression logistique
  * arbres de décision
  * méthodes de gradient boosting
* Optimisation des hyperparamètres par validation croisée

### 6. Évaluation des modèles

* Évaluation des performances à l’aide de métriques adaptées
* Analyse de l’importance des variables
* Comparaison des différents modèles

### 7. Déploiement et suivi

* Intégration du modèle de scoring dans un environnement de production
* Mise en place d’un suivi des performances dans le temps
* Recalibrage périodique du modèle si nécessaire

---

## Technologies utilisées

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Outils de machine learning pour la classification

---

## Résultats attendus

* Un modèle de scoring interprétable
* Une meilleure compréhension des facteurs de risque de défaut
* Un outil d’aide à la décision pour l’octroi de crédit

---

## Auteur

Projet réalisé dans un cadre d’apprentissage et de mise en pratique des techniques de data science et de machine learning appliquées au scoring crédit.
