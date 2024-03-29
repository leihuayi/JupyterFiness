# Exercice FINESS 📊

Le [FINESS](https://www.data.gouv.fr/fr/datasets/finess-extraction-du-fichier-des-etablissements/) contient la liste des établissements du domaine sanitaire et social.

C'est un répertoire central pour la HAS qui l'utilise notamment pour constituer la [BQSS](https://has-sante.pages.has-sante.fr/public/bqss/).

# Exemple de problématique métier

Une personne travaillant pour une institution publique de la Santé, souhaite réaliser une cartographie des établissements du domaine sanitaire et social.
Elle souhaite, par exemple, répondre aux questions suivantes:

- Pour une année donnée, combien d'établissements d'une catégorie donnée étaient enregistrés dans le FINESS.
- Évaluer l'évolution de la part de chaque catégorie d'établissements par année.
- Mesurer la répartition géographique des établissements sur le territoire français.

# But de l'exercice 🚀

Utilisez les données du FINESS pour étudier:

1. La répartition, dans l'export de 2024, du nombre d'établissement par catégorie
2. Mesurer l'évolution, entre 2018 et 2024 du nombre d'établissements enregistrés dans le FINESS.
3. Établir une carte des "Centres Hospitaliers Régionaux" (catégorie `1101`) en France.

Les éléments qui nous intéressent dans cet exercice sont:

- La capacité à appréhender un nouveau jeu de données
- La capacité à identifier les spécificités techniques d'un jeu de données
- La capacité à réaliser des choix pragmatiques dans les traitements effectués

> 📝 **Note :**
>
> - L'open-data du FINESS contient plusieurs fichiers, utilisez les bons en fonction du besoin
> - La structure des fichiers n'est pas forcément idéale, prenez le temps de bien les regarder
> - Pour la question de cartographie, vous pourrez utiliser la librairie `pyproj`

# En pratique 🛠

## Installation
```
# cloner le repo
git clone ...

# aller dans le bon dossier
cd JupyterFiness

# créer l'environnement python avec les bonnes librairies
conda create -n finess python=3.8 jupyter pandas matplotlib
```

## Lancer le notebook
```
# aller dans le bon dossier
cd JupyterFiness

# activer l'environnement python
conda activate finess

# lancer le notebook
jupyter notebook
```
