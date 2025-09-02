🔍 Insights & Findings
📈 Technical Findings

Data Quality & Preprocessing

The dataset contained missing values in the TotalCharges column, which were handled by imputing with the median.

customerID was dropped as it had no predictive power.

Categorical variables were encoded into numerical format for model compatibility.

Exploratory Data Analysis (EDA)

Tenure & Churn: Customers with shorter tenure had a significantly higher probability of churn.

Contract Type: Month-to-month contracts showed the highest churn rate, whereas customers on yearly contracts were more loyal.

Payment Method: Electronic check users churned more frequently compared to those using credit cards or bank transfers.

Services: Lack of multiple services (like internet + phone bundles) increased churn likelihood.

Feature Engineering

Derived features from categorical variables to capture customer behavior patterns.

Standardized numerical features (e.g., tenure, monthly charges) to improve model performance.

Model Building & Evaluation

Multiple models were tested (e.g., Logistic Regression, Random Forest, XGBoost).

Hyperparameter tuning was performed to optimize accuracy and recall.

The best-performing model achieved high accuracy and balanced precision-recall, making it suitable for churn detection.

💡 Business Insights

Customer Retention Risk: Short-tenure, month-to-month contract customers are most at risk of leaving.

Revenue Leakage: Customers on electronic check payments and single-service subscriptions contribute significantly to churn.

Retention Strategies:

Encourage long-term contracts through discounts or loyalty programs.

Target electronic check users with alternative, more stable payment methods.

Cross-sell bundled services (Internet + Phone + TV) to improve retention.

Predictive Model Utility: The churn prediction model enables proactive outreach — helping the business identify and engage at-risk customers before they churn.
