📊 Telco Customer Churn Prediction
📌 Project Overview

The objective of this project is to analyze the Telco Customer Churn dataset and build a predictive model to determine whether a customer is likely to churn.

Customer churn prediction is critical for telecom companies, as it helps in:

Reducing customer attrition

Increasing long-term profitability

Designing targeted retention strategies

📂 Dataset

Source: Telco Customer Churn dataset

Features: Customer demographics, account information, service usage, and contract/payment details

Target Variable: Churn (Yes/No)

🔧 Steps Performed

Data Preprocessing

Handled missing values (TotalCharges)

Dropped non-useful identifiers (customerID)

Encoded categorical variables

Standardized numerical features

Exploratory Data Analysis (EDA)

Distribution of customer demographics

Churn patterns across contract types, payment methods, and services

Correlation analysis of features

Feature Engineering

Created derived variables

Prepared balanced features for machine learning models

Model Building & Evaluation

Implemented Logistic Regression, Random Forest, and XGBoost

Performed hyperparameter tuning

Evaluated models with Accuracy, Precision, Recall, and F1-score

🔍 Insights & Findings
📈 Technical Findings

Customers with shorter tenure have higher churn probability.

Month-to-month contracts are the riskiest, while long-term contracts reduce churn.

Customers paying via Electronic Check churn more often.

Bundled services (Internet + Phone) increase retention.

The best model achieved strong accuracy and balanced precision-recall, making it reliable for churn detection.

💡 Business Insights

Retention Risk: New customers on flexible contracts are most likely to churn.

Revenue Leakage: Electronic check payment users churn disproportionately.

Strategies:

Promote long-term contracts with incentives

Encourage stable payment methods

Bundle services to improve loyalty

Value of Model: Helps proactively identify at-risk customers for timely engagement.

⚙️ Technologies Used

Python (pandas, NumPy, scikit-learn, matplotlib, seaborn, XGBoost)

Jupyter Notebook for development and documentation
