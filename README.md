# Atelier2_DeepLearning
# Université Abdelmalek Essaadi
# Faculté des Sciences et Techniques de Tanger
# Département Génie Informatique
# Pr. ELAACHAK Lotfi

## Introduction

Ce rapport présente les travaux que j'ai réalisés dans le cadre d'un atelier sur la classification d'images, en me concentrant sur deux approches : les réseaux de neurones convolutifs (CNN) et les Transformers pour la vision (ViT).

## Partie 1: CNN Classifier

Dans cette première partie, j'ai utilisé le dataset MNIST disponible sur Kaggle (lien : MNIST Dataset) pour développer un modèle de classification en utilisant des CNN. J'ai défini l'architecture du CNN en précisant les couches de convolution, de pooling, les couches entièrement connectées, ainsi que les hyper-paramètres tels que les noyaux, le padding, le stride, les optimiseurs et la régularisation. Le modèle a été exécuté en mode GPU pour accélérer les calculs. Ensuite, j'ai appliqué la méthode Faster R-CNN pour la détection d'objets sur le même dataset.

## Partie 2: Vision Transformer (ViT)

Dans cette deuxième partie, je me suis penché sur les Vision Transformers (ViT) qui ont pris une place prépondérante dans le domaine de la vision par ordinateur depuis leur introduction par Dosovitskiy et al. en 2020. J'ai suivi un tutoriel (Vision Transformers from Scratch - PyTorch) pour construire une architecture ViT à partir de zéro et l'appliquer à la tâche de classification sur le dataset MNIST.

## Conclusion

En conclusion, cet atelier m'a permis d'explorer et de comparer différentes approches de classification d'images, notamment les CNN, Faster R-CNN et ViT. Chaque approche présente des avantages et des inconvénients, et le choix dépend du contexte et des exigences spécifiques de la tâche de classification.
