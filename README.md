# Classification du Diabète

Ce dépôt contient du code et des ressources pour un projet de classification du diabète utilisant l'apprentissage automatique. Le projet inclut une application web pour prédire le statut diabétique en fonction des entrées de l'utilisateur.

## Table des matières

- [Aperçu](#aperçu)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Structure du projet](#structure-du-projet)
- [Contribution](#contribution)
- [Licence](#licence)

## Aperçu

L'objectif de ce projet est de construire un modèle prédictif pour classifier les individus comme diabétiques ou non diabétiques en fonction de mesures de santé spécifiques. Le modèle est déployé en utilisant Streamlit pour une interface web conviviale.

## Installation

Pour configurer le projet localement, suivez ces étapes :

1. Clonez le dépôt :
    ```sh
    git clone https://github.com/cheikht1/Diabete_classification.git
    ```
2. Accédez au répertoire du projet :
    ```sh
    cd Diabete_classification
    ```
3. Installez les dépendances requises :
    ```sh
    pip install -r requirements.txt
    ```

## Utilisation

Pour exécuter l'application web localement, utilisez la commande suivante :
```sh
streamlit run Web_app.py
```
## Structure du projet

-  ### diabetes.csv : Jeu de données utilisé pour l'entraînement du modèle.
-  ### trained_model.sav : Modèle de machine learning sauvegardé.
-  ### Predictive sys.py : Script pour le système de prédiction.
-  ### Web_app.py : Script de l'application web Streamlit.
-  ### Deploying_Machine_Learning_model_using_Streamlit.ipynb : Notebook Jupyter pour le déploiement du modèle avec Streamlit.

# Contribution
  Les contributions sont les bienvenues ! Veuillez fork le dépôt et créer une pull request avec vos modifications.
