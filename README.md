Telco Customer Churn Prediction

📌 Overview

This project focuses on predicting customer churn in a telecommunications company using machine learning techniques. Churn prediction is crucial for identifying customers likely to leave, enabling proactive retention strategies.

The dataset contains customer attributes such as service usage, account details, and demographics. Feature engineering, resampling, hyperparameter tuning, and model evaluation were applied to improve prediction accuracy.

🚀 Features of the Project


🔹 One-Hot Encoding – Converted categorical variables into numerical format for model compatibility.

🔹 Resampling (SMOTEENN) – Addressed class imbalance to enhance predictions for minority classes (churned customers).

🔹 Feature Scaling – Used MinMaxScaler to ensure uniform feature ranges.

🔹 Hyperparameter Tuning – Employed GridSearchCV and RandomizedSearchCV for optimal model selection.

🔹 Pipeline Automation – Integrated preprocessing and model evaluation into Scikit-learn pipelines for efficiency.


📊 Machine Learning Models Evaluated

The following models were tested and optimized:


✅ Random Forest

✅ Gradient Boosting

✅ Support Vector Machine (SVM)

✅ Logistic Regression

✅ K-Nearest Neighbors (KNN)

✅ Decision Tree

✅ AdaBoost

✅ XGBoost

✅ Naive Bayes

Each model underwent hyperparameter tuning, and their performance was compared using various evaluation metrics.


📈 Results & Performance Metrics

🔹 Best-performing model: (Mention the best model)

🔹 Accuracy: 99%

🔹 High Precision, Recall, and F1-score for churn prediction (Class 1).

🔹 Confusion Matrix & Bar Charts – Visualized model accuracy and classification errors.

📂 Project Structure
bash

📁 Telco-Customer-Churn-Prediction
│── 📄 README.md                               # Project documentation
│── 📄 Telco_Customer_Churn_Prediction.ipynb   # Jupyter Notebook with the full workflow
│── 📄 dataset.csv                             # Dataset used for training & testing
