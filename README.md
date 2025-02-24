# Mini-Project-1-Building-a-Sentiment-Analysis-System-for-Movie-Reviews-



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
- Nos résultats de l'analyse de l'emissions de carbone : 2.1070141533849448e-08

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

## Responsabilités liées à la publication du code
La publication du code source implique des responsabilités importantes en matière de transparence, de maintenance et d'accessibilité.

Le code fourni a été inspiré et tiré en partie du cours **GEI1092 - Techniques d'intelligence artificielle** de l'Université du Québec à Trois-Rivières. Ce cours lui-même s'appuie sur plusieurs ressources académiques et ouvrages de référence en apprentissage automatique et intelligence artificielle, notamment :  

1. **Raschka Sebastian, Vahid Mirjalili** – *Machine Learning and Deep Learning with Python, scikit-learn, and TensorFlow 2*, 3ᵉ édition, Packt Publishing, 2019.  
2. **Ian Goodfellow, Yoshua Bengio, Aaron Courville** – *Deep Learning*, The MIT Press, novembre 2016.  
3. **Raschka Sebastian** – *Build a Large Language Model*, 1ʳᵉ édition, Manning, octobre 2024.  
4. **Denis Rothman** – *Hands-On Explainable AI (XAI) with Python: Interpret, visualize, explain, and integrate reliable AI for fair, secure, and trustworthy AI*, 1ʳᵉ édition, Packt Publishing, juillet 2020.  
5. **Serg Masís** – *Interpretable Machine Learning with Python - Second Edition: Build explainable, fair, and robust high-performance models with hands-on, real-world examples*, 1ʳᵉ édition, Packt Publishing, octobre 2023.  
6. **CodeCarbon** : [https://mlco2.github.io/codecarbon/](https://mlco2.github.io/codecarbon/)  
7. **K. Lottick et al.** – *Energy Usage Reports: Environmental awareness as part of algorithmic accountability*, arXiv:1911.08354v2, 16 décembre 2019.  
8. **Peter Wentworth, Jeffrey Elkner, Allen B. Downey, Chris Meyers** – *How to Think Like a Computer Scientist: Learning with Python 3 Documentation*, 3ᵉ édition, février 2019.  


## Choix d'une licence open-source
Ce projet est sous licence MIT, qui permet une réutilisation libre tout en limitant la responsabilité des auteurs. D'autres licences open-source comme Apache 2.0 ou GPL v3 offrent des niveaux de protection différents en matière de brevets et de distribution.

## Impact des pratiques de publication
- **Transparence** : Publier un code bien documenté améliore la compréhension et l'auditabilité.
- **Collaboration** : Un projet open-source favorise les contributions externes via des pull requests.
- **Maintenance** : L'usage d'un suivi des versions et des issues permet une évolution continue du projet.

## Protocole de signalement et correction des bugs
1. **Suivi des problèmes** : Utilisation de GitHub Issues pour recenser les bugs et suggestions.
2. **Pull requests** : Processus structuré pour proposer des corrections et améliorations.
3. **Tests et validation** : Vérification des contributions avant leur intégration dans la branche principale.


## Installation et exécution
1. Cloner le dépôt :
  git clone https://github.com/D0ntMindMe/Mini-Project-1-Building-a-Sentiment-Analysis-System-for-Movie-Reviews-

cd sentiment-analysis-project

3. Installer les dépendances :
   pip install -r requirements.txt

4. Exécuter le script principal :
   python main.py
 

## Licence
Ce projet est sous licence MIT. 

