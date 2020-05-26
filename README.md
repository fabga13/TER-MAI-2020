# TER-MAI-2020
dernière maj 5/27

Le fichier denseNet121 se présente comme un notebook colab dans lequel se trouve en fait les 4 réseaux entrainés suivant:
DenseNet121
VGG16
VGG19
MobileNetV2
///////////////////////////////////////////

on y retrouve 2 dataset différent

100-bird-species
et
10-monkey-species

///////////////////////////////////////////

pour utiliser un dataset il faut lui enlever ses commentaires et passer l'autres en commentaire.

ainsi, une fois qu'un dataset est choisi, plusieurs paramètres lui sont spécifiques, à savoir :
-les data paths
-les image Data Generators
-la dernière couche dense de chaque modèle
-la fonction fit_generator

pour chaque paramètre, il faut retirer les commentaires pour le parametre correspondant au dataset choisi et mettre en paramettre sur le parametre correspondant à l'autre dataset

par défaut le dataset sélectionné est celui sur les espèces de singes.

///////////////////////////////////////////

Pour chaque modèle, il existe deux architectures, A1 selectionnée par defaut et A2 qui est entre commentaire, situé entre la couche lambda et la couche dense 200

///////////////////////////////////////////

ce git comprend les plots obtenus sur les deux dataset, 10-monkey-species et 100-bird-species, contenus repectivement dans les dossier singes/ et oiseaux/

