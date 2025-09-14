🫀 Heart Disease Prediction System
🚀 Overview
An end-to-end machine learning project that predicts the presence of heart disease in patients based on clinical features. The pipeline includes data preprocessing, feature engineering, model selection, evaluation, and deployment via a Flask API for real-time predictions. The project was implemented in Google Colab and is ready for GitHub sharing.

📂 Project Workflow

Data Preprocessing
• Handled missing values and outliers
• Encoded categorical variables using one-hot encoding
• Scaled numerical features for uniformity

Feature Engineering
• Selected key features impacting heart disease prediction
• Performed correlation analysis to remove multicollinearity
• Explored feature importance using tree-based models

Handling Imbalanced Data
• Applied SMOTE oversampling to balance the dataset

Modeling
• Tested multiple machine learning models:
– Logistic Regression
– Random Forest Classifier
– XGBoost Classifier
– Support Vector Machine (SVM)
• Ensembles: Voting Classifier combining LR, RF, and XGBoost

Evaluation
• Used Stratified K-Fold cross-validation
• Metrics reported: Accuracy, Precision, Recall, F1-score, ROC-AUC
• Visualized results with confusion matrices and ROC curves

Model Persistence & Deployment
• Saved trained models using joblib
• Built a Flask API to serve predictions
• Exposed API for real-time testing via ngrok

🎯 Key Features
• End-to-end heart disease prediction pipeline
• Handles imbalanced datasets using SMOTE
• Integrates ensemble machine learning models for robust predictions
• Provides visual insights with confusion matrices and feature importance plots
• Deployed with Flask + ngrok for instant API testing

📊 Performance
• Cross-validated performance ensures robustness
• Achieved high predictive accuracy across key metrics

🛠️ Tech Stack
• Languages: Python
• Libraries: pandas, NumPy, scikit-learn, imbalanced-learn, matplotlib, seaborn
• Model Persistence: joblib
• Frameworks: Flask, Jupyter Notebook
• Deployment: Flask API, ngrok

🔗 Dataset
The dataset used in this project can be accessed here:
👉 Google Drive – Heart Disease Dataset
