# Reconnaissance de la gestuelle dans le langage des signes

1. [Présentation](#presentation)
2. [Pour les développeurs](#developpeur)

---
### Présentation
Ce projet a été réalisé dans le cadre de l'UE Introduction à l'Apprentissage Supervisé intégré dans le programme de la 3ème année de  licence Informatique à l'Université Paris-Saclay.

Il consiste à implémenter un algorithme en python qui puisse identifier l'alphabet du langage des signes à partir d'images de mains récupérées dans une archive du site kaggle, archive disponible via [ce lien](https://www.kaggle.com/datamunge/sign-language-mnist).

L'idée est de comparer des classifiers de la bibliothèque Scikit-learn et de choisir celui qui renverra le meilleur score de prédiction sur notre jeu de données.

`Description de l'archive:` Les images de mains sont chiffrées dans des fichiers csv, elles sont décrites sous forme de pixels et associées à un label. Les labels sont numérotés de 0 à 24 représentent les lettres de l'alphabet (:warning: les lettres j et z ne sont pas représentées).

---

### Pour les développeurs
*[Projet terminé]*

Après plusieurs comparaisons de modèles d'apprentissage supervisé de la bibliothèque scikit-learn (SVC, NuSVC, DecisionTree), l'algorithme d'identification de l'alphabet se repose sur le modèle SVC.

`Idée d'approfondissement:`Le projet est ciblé sur l'identification de l'alphabet du langage des signes. Il pourrait être approfondi en incorporant des images de mains représentant des mots.

---

*Un grand bravo aux collaborateurs du projet  :heart: :blue_heart: :green_heart: :yellow_heart: :purple_heart: :black_heart:*





