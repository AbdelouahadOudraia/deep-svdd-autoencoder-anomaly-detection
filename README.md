# Détection d’Anomalies Hybride avec Deep SVDD et Autoencodeur

## Description

Ce projet implémente un modèle hybride de détection d’anomalies combinant :

* un autoencodeur (erreur de reconstruction)
* Deep SVDD (apprentissage basé sur la distance)

L’objectif est de détecter des anomalies dans des jeux de données d’images.

## Jeu de données

* MNIST
* Fashion-MNIST (si applicable)

## Résultats

* AUC > 97 %
* Bonne performance en détection d’anomalies

## Technologies

* Python
* PyTorch
* Scikit-learn

## Exécution

```bash
pip install -r requirements.txt
jupyter notebook
```

## Auteur

Abdelouahad Oudraia
