# Telco-Customer-Churn-Prediction
Telco Customer Churn Prediction
Overview
This project aims to predict customer churn in a telecommunications company using machine learning models. Churn prediction helps identify customers likely to leave, enabling businesses to implement retention strategies effectively.

The dataset includes various customer attributes, such as services availed, account information, and demographics. Preprocessing techniques, hyperparameter tuning, and resampling methods like SMOTEENN were employed to ensure high model performance and accuracy.

Features of the Project
One-Hot Encoding: Encoded categorical variables for model compatibility.

Resampling: Used SMOTEENN to address class imbalance and improve predictions for minority classes (churned customers).

Feature Scaling: Applied MinMaxScaler for consistent feature ranges.

Hyperparameter Tuning: Leveraged GridSearchCV and RandomizedSearchCV for model optimization.

Pipeline: Automated preprocessing and model evaluation using Scikit-learn pipelines.

Models Evaluated
The following machine learning models were evaluated:

Random Forest

Gradient Boosting

Support Vector Machine (SVM)

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

AdaBoost

XGBoost

Naive Bayes

Each model was tested with hyperparameter tuning, and their performance was compared.

Results
The overall best-performing model achieved:

Accuracy: 99%

High precision, recall, and F1-score for predicting churn (Class 1).

Detailed performance metrics for each model are visualized in a bar chart, showcasing their accuracy scores. Confusion matrices were also analyzed to understand prediction errors.
