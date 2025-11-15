📘 Customer Churn Prediction — Machine Learning Project

Predicting customer churn is essential for subscription-based businesses that aim to reduce customer loss and improve retention. This project builds a machine learning pipeline that identifies customers at risk of churning, enabling companies to take proactive action.

🎯 Objective

The goal of this project is to:

Analyze customer behavior

Build and evaluate ML models to predict churn
providig new data and test for accuracy.
Provide interpretable insights for decision-makers

📊 Dataset

Typical features include:

Customer Demographics: age, gender, region

Account Information: contract type, payment method, tenure

Financial Data: monthly/total charges

Target Variable: Churn (Yes/No)

🛠 Technologies Used

Python (3.x)

Pandas, NumPy

Scikit-Learn, XGBoost, LightGBM

Matplotlib, Seaborn

🔍 Exploratory Data Analysis (EDA)

The EDA notebook includes:

Churn distribution

Feature correlations

Tenure analysis

Impact of contract types

Insights help guide feature engineering and model selection.

🧹 Data Preprocessing

This pipeline includes:

Handling missing values

Encoding categorical variables (One-Hot/Label Encoding)
Handling class imbalance (SMOTE / class weights)

🤖 Modeling

Tested models include:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
XGB Classifier

Evaluation metrics:

F1-Score (important for churn)

Precision
