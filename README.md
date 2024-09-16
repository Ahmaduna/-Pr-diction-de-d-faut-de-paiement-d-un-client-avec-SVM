# Projet de Classification SVM pour la Prédiction de Défaut de Paiement

## Description du projet

Ce projet utilise des Support Vector Machines (SVM) pour prédire si un client sera en défaut de paiement le mois suivant, en se basant sur des informations de crédit et de comportement de paiement. Le projet utilise la base de données "UCI_Credit_Card" fournie par l'Université de Californie, Irvine (UCI).

## Contenu du projet

1. Chargement et exploration des données
2. Préparation des données
3. Création d'un modèle SVM initial
4. Optimisation des paramètres du modèle SVM
5. Évaluation des performances du modèle

## Dépendances

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Structure du projet

```
project/
│
├── SVM_Classification.ipynb    # Notebook Jupyter principal
├── UCI_Credit_Card.csv         # Fichier de données
└── README.md                   # Ce fichier
```

## Comment utiliser

1. Assurez-vous d'avoir toutes les dépendances installées.
2. Placez le fichier de données "UCI_Credit_Card.csv" dans le même répertoire que le notebook.
3. Ouvrez et exécutez le notebook "SVM_Classification.ipynb".

## Résultats

Le modèle SVM optimisé a atteint les performances suivantes sur l'ensemble de test :

- Accuracy : 0.650000
- Precision : 0.703448
- Recall : 0.512563
- F1 Score : 0.593023
- AUC : 0.707993

## Améliorations possibles

1. Essayer d'autres techniques de prétraitement des données.
2. Expérimenter avec d'autres algorithmes de classification.
3. Utiliser des techniques d'ensemble pour améliorer les performances.
4. Effectuer une analyse plus approfondie des caractéristiques importantes.

