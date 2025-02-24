# Détection des maladies cardiovasculaires

## Description
Ce projet utilise l'apprentissage automatique pour prédire la présence de maladies cardiovasculaires à partir de données médicales. Plusieurs modèles de machine learning ont été testés afin de trouver le plus performant.

## Technologies utilisées
- Python
- Pandas, Numpy, Seaborn, Matplotlib (Visualisation et traitement des données)
- Scikit-Learn (Modèles de machine learning)
- XGBoost, AdaBoost, RandomForest (Ensembles d'apprentissage)

## Modèles testés
- Régression Logistique
- Support Vector Machine (SVM)
- Arbres de décision
- XGBoost (Meilleur modèle avec une accuracy d'environ 80% et un recall de 94%)

## Installation
1. Cloner le dépôt GitHub :
   ```bash
   git clone https://github.com/yelwali/cardio.git
   ```
2. Installer les dépendances :
   ```bash
   pip install -r requirements.txt
   ```

## Utilisation
1. Charger le dataset dans le dossier `data/`.
2. Exécuter le script principal :
   ```bash
   python main.py
   ```
3. Les résultats de la classification seront affichés avec des métriques de performance.

## Résultats et Analyse
L'algorithme **XGBoost** s'est avéré être le plus performant avec :
- **Accuracy :** ~80%
- **Recall :** ~94%

Ces performances montrent que le modèle est efficace pour la détection précoce des maladies cardiovasculaires.

## Auteur
[Youssef El Wali](https://www.linkedin.com/in/youssef-el-wali-7b7765263)
