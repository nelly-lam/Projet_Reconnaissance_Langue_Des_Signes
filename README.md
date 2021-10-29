# Reconnaissance de la gestuelle dans le langage des signes

1. [Présentation](#presentation)
2. [Pour les développeurs](#developpeur)

---
### Présentation
Ce projet a été réalisé dans le cadre de l'UE Introduction à l'Apprentissage Supervisé intégré dans le programme de la 3ème année de  licence Informatique à l'Université Paris-Saclay.

Il consiste à implémenter un algorithme en python qui puisse identifier l'alphabet du langage des signes à partir d'images de mains récupérées dans une archive du site kaggle, archive disponible via [ce lien](https://www.kaggle.com/datamunge/sign-language-mnist).

L'idée est de comparer des classifiers de la bibliothèque Scikit-learn et de choisir celui qui renverra le meilleur score de prédiction sur notre jeu de données.

`Description de l'archive:` Les images de mains sont chiffrées dans des fichiers csv, elles sont décrites sous forme de pixels et chacune associée à un label. Les labels sont numérotés de 0 à 24 et représentent les lettres de l'alphabet (:warning: les lettres j et z ne sont pas représentées).

---

### Pour les développeurs
*[Projet terminé]*

Après plusieurs comparaisons de modèles d'apprentissage supervisé de la bibliothèque scikit-learn (SVC, NuSVC, LinearSVC, DecisionTree), l'algorithme d'identification de l'alphabet se repose sur le modèle SVC.

`Idée d'approfondissement:` Le projet est ciblé sur l'identification de l'alphabet du langage des signes. Il pourrait être approfondi en incorporant des images de mains représentant des mots.

---
---

[eng version]

1. [Presentation](#presentation)
2. [For developers](#developer)

---
### Presentation
This project was realized for the Introduction to Supervised Learning course, 
of the program of the 3rd year of Computer Science degree at the University Paris-Saclay.

It consists in implementing an algorithm in python that can identify the alphabet of the sign language from images of hands recovered in an archive of the site kaggle, archive available via [this link](https://www.kaggle.com/datamunge/sign-language-mnist).

The idea is to compare classifiers from the Scikit-learn library and choose the one that will return the best prediction score on our data set.

`Description of the package:` The hand images are encrypted in csv files, they are described as pixels and each associated with a label. 
The labels are numbered from 0 to 24 and represent the letters of the alphabet (:warning: the letters j and z are not represented).

---

### For developers
*[Project completed]*

After several comparisons of supervised learning models from the scikit-learn library (SVC, NuSVC, LinearSVC, DecisionTree), 
we finally choose that the alphabet identification algorithm would be based on the SVC model.

`Improvement:` The project is focused on identifying the sign language alphabet. 
It could be further developed by incorporating pictures of hands representing words.


---

*Un grand bravo aux collaborateurs du projet  :heart: :blue_heart: :green_heart: :yellow_heart: :purple_heart: :black_heart:*





