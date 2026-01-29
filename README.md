# Classification d'Images (Chats vs Chiens) avec PyTorch

## Description du Projet
[cite_start]Ce projet a été réalisé dans le cadre d'un mini-projet de Machine Learning[cite: 1, 2]. [cite_start]L'objectif est de construire et d'améliorer systématiquement un modèle de réseau de neurones convolutifs (CNN) pour classifier des images de chats et de chiens[cite: 4, 7].

## Dataset
* [cite_start]**Source** : Kaggle (`chetankv/dogs-cats-images`)[cite: 15, 34].
* **Contenu** : 10 000 images (8 000 entraînement / 2 000 test).
* **Format** : Images redimensionnées en 64x64 pixels.

## Architecture et Expériences
[cite_start]Le projet suit une démarche d'amélioration continue[cite: 4, 55]:
* **Baseline** : CNN simple avec SGD (Précision : ~64.8%).
* **Expérience 1** : Optimiseur Adam pour une meilleure convergence.
* [cite_start]**Expérience 2** : Utilisation de la **Data Augmentation** (rotations, flips) pour réduire le surapprentissage (overfitting)[cite: 56].
* **Expérience 3** : Architecture plus profonde avec 3 couches de convolution.

## Résultats Principaux
[cite_start]L'amélioration la plus significative a été obtenue grâce à la **Data Augmentation**, permettant d'atteindre une précision de **77.4%** sur l'ensemble de test[cite: 56, 57].

## Installation et Utilisation
Le projet a été développé sur Google Colab. 
> **Note de sécurité** : L'accès aux données Kaggle utilise la fonctionnalité "Secrets" de Colab pour protéger les clés API. Pour exécuter ce notebook, vous devrez configurer vos propres variables `KAGGLE_USERNAME` et `KAGGLE_KEY` dans l'onglet Secrets de Colab.

## Livrables
* `officiel_de_Untitled4.ipynb` : Script complet du projet.
* [cite_start]`ML_PROJECT_Rapport.pdf` : Rapport détaillé des expériences[cite: 50, 53].
