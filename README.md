# Prévision du Trafic des Passagers Aériens

## Description du Projet

Ce projet vise à prévoir le trafic des passagers aériens en utilisant des techniques de modélisation de séries temporelles, notamment les modèles ARIMA, les réseaux de neurones à longue mémoire à court terme (LSTM) et les réseaux de neurones artificiels (ANN). L'objectif est de comparer les performances de ces modèles pour la prévision de séries temporelles, en utilisant des données historiques sur le nombre de passagers aériens.

## Contenu du Projet

### 1. Fichiers Principaux
- **Airline Passengers Traffic Forecasting using ARIMA Model&LSTM&ANN.ipynb** : Le notebook Jupyter contenant le code pour l'analyse des données, la modélisation et la prévision du trafic des passagers aériens.
- **AirPassengers.csv** : Le fichier CSV contenant les données historiques du nombre de passagers aériens.
- **stationary.csv** : Un fichier CSV contenant les données après transformation pour rendre la série temporelle stationnaire.
- **train_data.csv** : Données d'entraînement pour les modèles.
- **test_data.csv** : Données de test pour évaluer la performance des modèles.


## Outils et Technologies Utilisés
- **Python** : Langage principal utilisé pour le développement.
- **Pandas** : Pour la manipulation et l'analyse des données.
- **Matplotlib & Seaborn** : Pour la visualisation des données et des résultats des modèles.
- **Numpy** : Pour les calculs numériques.
- **TensorFlow & Keras** : Pour le développement et l'entraînement des modèles LSTM et ANN.

## Étapes pour Exécuter le Projet

1. **Installation des Dépendances**
   Assurez-vous d'avoir les bibliothèques Python suivantes installées :
   ```bash
   pip install pandas matplotlib seaborn numpy tensorflow keras
