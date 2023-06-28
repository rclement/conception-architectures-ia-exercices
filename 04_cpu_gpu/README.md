# Exercice - Comparaison de performance CPU / GPU

Observons la différence de performance d'exécution sur CPU et GPU pour un processus d'entraînement d'un modèle par apprentissage profond (Deep Learning).

Afin de pouvoir comparer les performances sur plusieurs architectures matérielles, il est conseillé d'utilise plateform [Google Colab](https://colab.research.google.com) permettant de sélectionner l'accélération matérielle souhaitée à la volée.

Egalement, si votre machine personnelle est équipée et configurée pour utiliser un GPU NVidia avec Tensorflow, vous pouvez réaliser l'activité en local.

> **Note**
>
> Pour changer le type de matériel utilisé sur Google Colab après chargement d'un notebook :
> 1. Cliquer sur le menu "Edit" puis "Notebook settings"
> 2. Sélectionner une valeur dans "Hardware accelerator" (`None` signifie CPU)

## Instructions

En individuel, ouvrir le notebook Jupyter `fashion_classifier.ipynb` via la [plateforme Google Colab](https://colab.research.google.com/github/rclement/conception-architectures-ia-exercices/blob/main/04_cpu_gpu/fashion_classifier.ipynb).

Effectuer **2 exécutions** successives du notebook en sélectionnant d'abord le **mode CPU puis GPU** :
1. Lire attentivement les instructions avant chaque cellule
2. Exécuter chaque cellule de code et analyser le résultat
3. Répondre aux questions en fin de notebook
