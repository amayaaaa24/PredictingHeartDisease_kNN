# PredictingHeartDisease_kNN

This project aims to predict the likelihood of an individual developing heart disease using machine learning. Early detection of heart disease is crucial for timely intervention and improved patient outcomes. The project utilizes a dataset of patient information, including demographics, medical history, and diagnostic data, to build and evaluate predictive models.

## Data

The dataset used in this project can be found [here](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction). It contains various features, including age, gender, chest pain type, cholesterol levels, fasting blood sugar, and more, along with the target variable indicating the presence or absence of heart disease.
- heart_disease_prediction.csv

## Model Building
We use scikit-learn to build machine learning models for heart disease prediction.
The selected features include age, gender, chest pain type, cholesterol, fasting blood sugar, and others.
Different algorithms are employed to train and evaluate models.

## Hyperparameter Tuning
GridSearchCV is used to fine-tune model hyperparameters.
Parameters like the number of nearest neighbors, weights, and metrics are optimized to improve model accuracy.
Results
The project achieves a significant accuracy improvement through hyperparameter tuning, increasing accuracy by approximately 6%.
Detailed results and model performance can be found in the project notebooks.

For a more detailed analysis and insights, please refer to the PredictingHeartDisease.ipynb notebook.
