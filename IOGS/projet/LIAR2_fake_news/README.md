---


# Détection de "Fake news"



---

L'objectif est de prédire si des déclarations sont vraies ou fausses.

Les données sont celles de la base LIAR2

- accessible depuis Hugging Face: https://huggingface.co/datasets/chengxuphd/liar2 
- ou depuis le Github https://github.com/chengxuphd/liar2 qui contient des codes et des références.

Pour manipuler le texte (l'encoder), vous pouvez utiliser des techniques classiques de style "bag of words" ou utiliser un modèle de langage.

La prédiction pourra s'appuyer sur la déclaration brute, ou sur d'autres éléments d'information présents dans la base.

Un notebook jupyter pour vous aider à démarrer est disponible ici: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stepherbin/teaching/blob/master/IOGS/projet/LIAR2_Fake_News/fake_test.ipynb)
