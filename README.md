# Classification d'Images (Chats vs Chiens) avec PyTorch

## Description du Projet
Ce projet a été réalisé dans le cadre d'un mini-projet de Machine Learning. L'objectif était de construire un modèle de réseau de neurones performant. Notre choix s'est porté sur une architecture de réseau de neurones convolutifs (CNN) pour classifier des images de chats et de chiens. Par la suite, nous avons mené différentes expériences systématiques afin d'identifier les paramètres et les techniques d'optimisation permettant d'obtenir le modèle le plus efficace

## Dataset
**Source** : Kaggle (`chetankv/dogs-cats-images`).
* **Contenu** : 10 000 images (8 000 entraînement / 2 000 test).
* **Format** : Images redimensionnées en 64x64 pixels.

## Architecture et Expériences
Le projet suit une démarche d'amélioration continue:
* **Baseline** : CNN simple avec SGD (Précision : ~64.8%).
* **Expérience 1** : Optimiseur Adam pour une meilleure convergence.
* **Expérience 2** : Utilisation de la **Data Augmentation** (rotations, flips) pour réduire le surapprentissage (overfitting).
* **Expérience 3** : Architecture plus profonde avec 3 couches de convolution.

## Résultats Principaux
L'amélioration la plus significative a été obtenue grâce à la **Data Augmentation**, permettant d'atteindre une précision de **77.4%** sur l'ensemble de test.

## Installation et Utilisation
Le projet a été développé sur Google Colab. 
> **Note de sécurité** : L'accès aux données Kaggle utilise la fonctionnalité "Secrets" de Colab pour protéger les clés API. Pour exécuter ce notebook, vous devrez configurer vos propres variables `KAGGLE_USERNAME` et `KAGGLE_KEY` dans l'onglet Secrets de Colab.

## Livrables
* `officiel_de_Untitled4.ipynb` : Script complet du projet.
* `ML_PROJECT_Rapport.pdf` : Rapport détaillé des expériences.
