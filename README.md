❤️ Heart Disease Prediction System
🚀 Overview

An end-to-end Machine Learning system that predicts the risk of heart disease in patients based on clinical features. The pipeline integrates data preprocessing, feature engineering, model training, evaluation, and deployment with a Flask API for real-time predictions.

📂 Project Workflow
1. Data Preprocessing

Handled missing values and outliers

Converted categorical features to numerical via encoding

Standardized numerical features for model readiness

2. Feature Engineering

Explored feature importance using correlation and statistical analysis

Scaled features using MinMaxScaler / StandardScaler for better model performance

3. Handling Imbalanced Data

Applied SMOTE oversampling to balance classes of heart disease presence/absence

4. Modeling

Tested multiple ML models with emphasis on:

Random Forest

Gradient Boosting

Logistic Regression

Support Vector Machine

5. Evaluation

Used Stratified K-Fold cross-validation

Reported Accuracy, Precision, Recall, F1-score, ROC-AUC

Visualized results with confusion matrices and feature importance plots

6. Model Persistence & Deployment

Saved trained models, encoders, and scalers using joblib

Built a Flask API for serving predictions

Exposed API via ngrok for instant global access

🎯 Key Features

End-to-end heart disease prediction pipeline

Handles imbalanced data with SMOTE

Robust performance using Random Forest & Gradient Boosting

Provides visual insights (feature importance, confusion matrix)

Deployed via Flask API + ngrok for real-time predictions

📊 Performance

Evaluated using multiple metrics (Accuracy, Precision, Recall, F1, ROC-AUC)

Cross-validation ensures reliable performance across different patient data subsets

🛠️ Tech Stack

Languages: Python

Libraries: pandas, NumPy, scikit-learn, imbalanced-learn, matplotlib, seaborn

Model Persistence: joblib

Frameworks: Flask, Jupyter Notebook

Deployment: Flask API, ngrok

🔗 Dataset

The dataset used in this project can be accessed here:
👉 Google Drive – Heart Disease Dataset
