# Ségmentation d'images médicales avec Deep Learning dans le cadre du cursus à EPITA

Ce projet utilise des techniques de Deep Learning pour segmenter des images médicales. Le but est de développer un modèle capable de détecter et de segmenter les régions d'intérêt dans les images médicales.

## Introduction

Les images médicales sont un outil essentiel pour le diagnostic et le traitement des maladies. Cependant, l'analyse manuelle de ces images peut être fastidieuse et sujet à erreur. Les techniques de Deep Learning peuvent aider à automatiser cette tâche et améliorer la précision du diagnostic.

## Architecture du projet

Ce projet utilise une architecture de Deep Learning basée sur les réseaux de neurones convolutionnels (CNN). Le modèle est entraîné sur un jeu de données d'images médicales annotées.

## Dépendances

* `numpy`
* `pandas`
* `matplotlib`
* `scikit-image`
* `scikit-learn`
* `tensorflow` ou `pytorch`
* `jupyter`
* `notebook`

## Installation

Pour installer les dépendances, exécutez la commande suivante :
```bash
pip install -r requirements.txt
```

## Téléchargement du jeu de données

Pour utiliser ce projet, vous devez télécharger le jeu de données iSeg2017 à l'adresse suivante :
https://iseg2017.web.unc.edu/download/ 

Ce jeu de données contient des images médicales annotées qui seront utilisées pour entraîner et tester le modèle.

## Utilisation

Une fois le jeu de données téléchargé et les dépendances installées vous pouvez adapter le chemin d'accès aux données directement dans le code du notebook

## Auteur

NAMAOUI Radhwane