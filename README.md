# Conception des Architectures IA - Exercices

Ce dépôt Git contient les exercices techniques du module "Conception des Architectures IA" :

1. [Extraction de données](01_extraction/README.md)
2. [Pré-traitement de données](02_preprocessing/README.md)
3. [Machine Learning](03_machine_learning/README.md)
4. [CPU vs GPU](04_cpu_gpu/README.md)

## Mise en place

Pour réaliser les exercices, vous pouvez utiliser un environnement local ou bien passer par GitHub Codespaces directement.

### (recommandé) GitHub Codespaces

**Si vous n'avez pas l'habitude de gérer des environnements virtuels Python sur votre machine**, il est conseillé d'utiliser le service [GitHub Codespaces](https://docs.github.com/fr/codespaces). Ce service permet de démarrer un environnement dans un conteneur Docker prêt à l'emploi à partir d'un dépôt GitHub.

> **Note**
>
> Chaque utilisateur de GitHub bénéficie **gratuitement** de [120 "coeur-heures" et 15 Go de stockage par mois](https://docs.github.com/en/billing/managing-billing-for-github-codespaces/about-billing-for-github-codespaces#monthly-included-storage-and-core-hours-for-personal-accounts).
> Ce quota est plus que nécessaire pour réaliser ces exercices dans son intégralité !

Pour démarrer un Codespace avec le [dépôt GitHub](https://github.com/rclement/conception-architectures-ia-exercices), cliquez sur ce bouton :

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/rclement/conception-architectures-ia-exercices?quickstart=1)

> **Warning**
>
> Après avoir terminé les exercices, n'oubliez pas [d'éteindre votre Codespace](https://docs.github.com/fr/codespaces/developing-in-codespaces/stopping-and-starting-a-codespace) pour ne pas consommer votre crédit d'utilisation :
> - Cliquer sur le bouton en bas à gauche "Codespace" puis "Stop the current Codespace"
> - Se rendre sur la [page des Codespaces](https://github.com/codespaces), cliquer sur le menu contextuel du Codespace puis "Arrêter le Codespace"
>
> Vous pouvez ensuite supprimer définitivement votre Codespace si vous le souhaitez (vous perdrez les données générées sur la machine virtuelle).

### En local

**Si vous êtes familier avec la gestion d'environnements virtuels Python sur votre machine** (en utilisant `venv` + `pip`, `pipenv`, `poetry`, ou `pipx`) :

1. Cloner le dépôt Git de l'atelier :
```bash
git clone https://github.com/rclement/conception-architectures-ia-exercices.git
cd conception-architectures-ia-exercices
```

2. Créer un environnement virtuel et installer les dépendances (par exemple, en utilisant `venv` et `pip`) :

Sous Linux ou macOS :
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Sous Windows :
```bash
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
```
