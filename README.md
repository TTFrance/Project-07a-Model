# Project-07

# Openclassrooms Data Scientist Project 7, Adam Phillips

- Supervised learning sur un jeu de données déséquilibré (pénalisation des classes par Undersampling)
- Choix d'une métrique adaptée à un problème métier
- Construction d'un modèle de scoring supervisé
- Mise en place d'une API pour appeler le modèle de prédiction (FastAPI/Heroku) 
- Construction d'un dashboard interactif à destination des gestionnaires de relation client (Streamlit)
- Utilisation de github pour versioning

# Installation
- L'installation est recommandée dans un environnement Anaconda contenant:
  - pandas
  - seaborn
  - numpy
  - matplotlib
  - dill
  - scikit-learn
  - scipy
  - lightgbm
  - joblib
  - pickle
  - xgboost
  - shap
  
# Usage
- INPUT DATA
  - toutes les données input doivent résider dans un dossier appelé data/raw/. 
  - Le dossier 'data' doit être au même niveau que le dossier du projet
- OUTPUT
  - Data
    - résidera dans un sous-dossier du dossier de données, appelé "cleaned"
  - Models
    - résidera dans un sous-dossier du dossier du projet, appelé 'model'
- Execution
  - Lancez:
    - 01 MERGING.ipynb (fusionne les données)
    - 02 CLEANING.ipynb (nettoie les données)
    - 03 MODELLING NEW DATA.ipynb (sélection du modèle)
    - CREATE DASHBOARD CLIENT 1K FILES.ipynb (création de tranches de données pour tableau de bord, API)
