# 🏥 Détection des maladies cardiovasculaires avec l'IA  

## 📌 Description  
Ce projet vise à prédire la présence de maladies cardiovasculaires à l'aide de l'apprentissage automatique. Plusieurs modèles de machine learning ont été testés et optimisés pour obtenir les meilleures performances.  

## 📊 Prétraitement des données  
- Imputation des valeurs manquantes avec **KNNImputer**  
- Normalisation des données avec **RobustScaler**  
- Équilibrage des classes avec **SMOTE** pour éviter le déséquilibre des données  

## 🏆 Modèles utilisés et performances  
| Modèle            | Accuracy | Recall  |
|------------------|----------|---------|
| Régression linéaire  | 0.565  | 0.612  |
| Decision Tree       | 0.737  | 0.907  |
| XGBoost            | 0.738  | 0.912  |
| AdaBoost           | 0.738  | 0.935  |
| RandomForest       | 0.746  | 0.907  |

📌 **Meilleurs modèles** :  
- **RandomForest** : Accuracy = **0.746**, Recall = **0.907**  
- **AdaBoost** : Accuracy = **0.738**, Recall = **0.935**  

## 🚀 Optimisation  
- Recherche des hyperparamètres avec **GridSearchCV**  
- Sélection des meilleures features avec **SHAP values**  
- Test de différentes méthodes d'équilibrage (SMOTE, ADASYN)  

## 🛠 Technologies utilisées  
- **Python** (Scikit-learn, XGBoost, Pandas, Matplotlib, Seaborn)  
- Jupyter Notebook pour l'analyse des données  

## 📂 Structure du projet  

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

## Auteur
[Youssef El Wali](https://www.linkedin.com/in/youssef-el-wali-7b7765263)
