# Projet de détection et localisation de feux avec l'IA

## Description du projet

Ce projet vise à développer un système de détection et de localisation de feux, de départs de feu et de fumée à partir d'images et de vidéos. Nous avons utilisé des réseaux de neurones profonds pour classifier les images en trois catégories : **feu**, **départ de feu** et **absence de feu**. En complément, nous avons également implémenté un modèle de localisation basé sur **YOLO** pour identifier les zones de feu et de fumée dans les images.

### Fonctionnalités principales

1. **Classification des images** : Utilisation de modèles de deep learning (ResNet, VGG16, GoogleNet, EfficientNet, Vision Transformers) pour classifier les images.
2. **Localisation des feux** : Utilisation de YOLO pour détecter et localiser les zones de feu et de fumée dans les images.
3. **Tests en temps réel** : Application des modèles sur des vidéos pour évaluer leurs performances en conditions réelles.

## Résultats clés

- **Meilleur modèle** : **ResNet152** a montré les meilleures performances en termes de précision et de généralisation.
- **Vision Transformers (ViT)** : Bien que prometteurs, les ViT nécessitent une optimisation supplémentaire pour rivaliser avec les modèles CNN traditionnels.
- **Localisation avec YOLO** : Le modèle YOLO a permis une détection précise des zones de feu et de fumée, même dans des scènes complexes.

## Vidéos de démonstration

Nous avons testé nos modèles sur des vidéos réelles et annoté les résultats. Voici les liens vers les vidéos démontrant les performances de nos modèles :

1. **Détection de feu, départ de feu et absence de feu** :  
   [Vidéo de détection](https://youtu.be/_klmNDs02vY)

2. **Localisation des zones de feu et de fumée avec YOLO** :  
   [Vidéo de localisation](https://youtu.be/vq-laiUJwVO)

3. **Combinaison de détection et localisation** :  
   [Vidéo combinée](https://youtu.be/bBL225O-4Jc)

## Comment utiliser

1. **Télécharger les données** : Les données utilisées pour ce projet sont disponibles sur [Nextcloud](https://nextcloud.lg.umons.ac.be/s/RsZpgtYfDgYzKxr).
2. **Entraîner les modèles** : Les scripts pour entraîner les modèles sont fournis dans le dépôt. Utilisez `train_resnet.py`, `train_yolo.py`, etc., pour entraîner chaque modèle.
3. **Tester sur des vidéos** : Utilisez les scripts de test pour appliquer les modèles sur des vidéos et évaluer leurs performances.

## Auteurs

- **Nicolas Melaerts** - Développeur du projet.
- **Manu Mathey** - Développeur du projet.

## Références

- **ResNet** : [Article original](https://arxiv.org/pdf/1512.03385)
- **YOLO** : [Site officiel](https://pjreddie.com/darknet/yolo/)
- **Vision Transformers** : [Article original](https://arxiv.org/abs/2010.11929)
