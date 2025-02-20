# Mini-Project-1-Building-a-Sentiment-Analysis-System-for-Movie-Reviews-

# Description en francais suivra.

# Mini Project 1: Sentiment Analysis System for Movie Reviews

## Introduction
Ce projet consiste à développer un système d'analyse de sentiment appliqué à des critiques de films, en utilisant la régression logistique. En plus de l'entraînement et de l'évaluation du modèle, nous mesurerons son empreinte carbone avec la bibliothèque CodeCarbon, aborderons les implications éthiques et considérerons son déploiement sur des systèmes embarqués.

## Objectifs
1. **Préparation des données** : Chargement et exploration du jeu de données IMDb.
2. **Prétraitement des textes** : Nettoyage et transformation des données textuelles.
3. **Extraction de caractéristiques** : Vectorisation des critiques de films en utilisant TF-IDF.
4. **Entraînement du modèle** : Utilisation de la régression logistique pour la classification.
5. **Évaluation du modèle** : Calcul des métriques de précision, rappel et score F1.
6. **Ajustement des hyperparamètres** : Optimisation du modèle avec Grid Search.
7. **Analyse des courbes d'apprentissage** : Diagnostic de l'overfitting et de l'underfitting.
8. **Analyse de l'empreinte carbone** : Utilisation de CodeCarbon pour mesurer les émissions de CO2.
9. **Considérations éthiques** : Explicabilité des résultats avec SHAP et discussion sur l'impact sociétal.
10. **Déploiement sur systèmes embarqués** : Conversion du modèle pour exécution sur un microcontrôleur.

## Données
- Le jeu de données IMDb peut être téléchargé [ici](https://ai.stanford.edu/~amaas/data/sentiment/).

## Prétraitement des données
- Suppression des caractères inutiles (balises HTML, ponctuation)
- Conversion en minuscules
- Suppression des mots vides
- Stemming et lemmatisation

## Entraînement et évaluation du modèle
- Séparation des données en ensembles d'entraînement et de test
- Entraînement de la régression logistique
- Évaluation à l'aide des métriques : précision, rappel, score F1
- Visualisation de la matrice de confusion

## Ajustement des hyperparamètres
- Utilisation de Grid Search pour trouver les meilleurs paramètres (‘C’, ‘penalty’, ‘solver’)

## Suivi de l'empreinte carbone
- Intégration de CodeCarbon pour mesurer la consommation d'énergie
- Comparaison des émissions en fonction des paramètres du modèle

## Considérations éthiques
- Utilisation de SHAP pour comprendre l'impact des mots sur les prédictions
- Analyse des biais et de l'équité du modèle

## Déploiement sur systèmes embarqués
- Extraction des poids et biais du modèle
- Quantification en nombres entiers pour l'exécution sur microcontrôleurs
- Génération d'un fichier header C++ contenant les coefficients

## Documentation et publication du code
- Rédaction d'une documentation complète
- Ajout d'une licence open-source (MIT)
- Mise en place d'un protocole de signalement des bugs (issues, pull requests)

## Installation et exécution
1. Cloner le dépôt :
  git clone https://github.com/D0ntMindMe/Mini-Project-1-Building-a-Sentiment-Analysis-System-for-Movie-Reviews-

cd sentiment-analysis-project

3. Installer les dépendances :
   pip install -r requirements.txt

4. Exécuter le script principal :
   python main.py
 

## Licence
Ce projet est sous licence MIT. Voir `LICENSE` pour plus de détails.

