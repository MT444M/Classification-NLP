# README pour les Notebooks de Classification NLP dans le Domaine Juridique

## Introduction

Ce projet consiste en deux notebooks Jupyter dédiés à la classification de textes dans le domaine juridique. Nous utilisons des techniques de traitement du langage naturel (NLP) pour classifier des documents juridiques en différentes catégories. Les notebooks sont structurés comme suit :

- **Classif_JuriBERT.ipynb** : Utilise un modèle NLP personnalisé, JuriBERT, spécifiquement entraîné pour comprendre le langage juridique.
- **Classif_CamemBert.ipynb** : Emploie le modèle CamemBERT, un modèle de langue pré-entraîné sur des données en français, adapté à la classification de textes juridiques.

## Datasets

Les données utilisées pour l'entraînement et la validation des modèles proviennent de la plateforme Hugging Face, sous l'identifiant `/SBARD`. Ce dataset contient une variété de documents juridiques annotés, permettant de réaliser une classification fine et précise.

## Modèles

### CamemBERT

- **Source** : Le modèle CamemBERT est disponible sur Hugging Face sous l'identifiant `Huggingface/camemBert`. Il s'agit d'un modèle de langue basé sur Transformer, pré-entraîné sur un large corpus de textes en français.
- **Utilisation** : Dans le notebook `Classif_CamemBert.ipynb`, nous adaptons CamemBERT à notre tâche de classification juridique en fine-tuning le modèle sur notre dataset spécifique.

### JuriBERT

- **Source** : JuriBERT est un modèle NLP développé par http://nlp.polytechnique.fr/resources#juribert et spécifiquement entraîné sur des textes juridiques. Ce modèle n'est pas public et est utilisé exclusivement dans le cadre de ce projet.
- **Utilisation** : Le notebook `Classif_JuriBERT.ipynb` détaille comment nous entraînons et utilisons JuriBERT pour classer les documents juridiques.

## Structure des Notebooks

Chaque notebook contient les sections suivantes :

1. **Introduction et Contexte** : Présentation du projet, des objectifs, et du contexte spécifique de chaque modèle.
2. **Préparation des Données** : Détails sur le chargement, l'exploration, et la préparation des données pour l'entraînement.
3. **Modélisation** : Explications sur le choix du modèle, sa configuration, et le processus d'entraînement.
4. **Évaluation** : Méthodes et résultats de l'évaluation des modèles, incluant la précision, la matrice de confusion, et d'autres métriques pertinentes.


## Contact

Pour toute question ou suggestion, n'hésitez pas à contacter les auteurs du projet.
