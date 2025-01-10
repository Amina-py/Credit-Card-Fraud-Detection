# Credit-Card-Fraud-Detection
This project focuses on analyzing and predicting credit card fraud using SQL, Python, and Power BI. The aim is to identify patterns in fraudulent transactions and build a robust predictive model for real-time fraud detection. The dataset used was gotten from [kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data).

## Key Insights:
Fraudulent transactions account for 17.26% of all cases but involve 58% higher average transaction amounts than non-fraudulent transactions. 
Fraud patterns were analyzed using SQL, revealing the financial impact and rarity of fraudulent cases.

Predictive Modeling:
Addressed class imbalance using anomaly detection and synthetic data generation (SMOTE).
Trained and evaluated two models:
Random Forest Classifier: Accuracy = 1.00, ROC-AUC = 0.9345
Logistic Regression: Accuracy = 0.97, ROC-AUC = 0.9345
Models were saved using Joblib for deployment.

## Conclusion:
This analysis provides actionable insights and deployable models for fraud detection. Continuous monitoring, feature enhancement, and collaboration are recommended to maintain and improve the system’s effectiveness.
