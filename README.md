# 🏦 Bank Customer Churn Prediction

An end-to-end Machine Learning project to predict customer churn in a banking environment and support data-driven customer retention strategies.

---

## 📌 Project Objective
Customer churn leads to revenue loss and increased acquisition costs.  
The objective of this project is to build a predictive model that identifies customers likely to leave the bank, enabling proactive retention actions.

---

## 💼 Business Impact
This solution can help banks:

- Reduce customer attrition
- Improve customer lifetime value
- Enable targeted retention campaigns
- Improve customer engagement strategies

---

## 📊 Dataset Overview
The dataset contains customer banking information including:

- Customer demographics (Age, Gender, Geography)
- Account details (Balance, Credit Score, Tenure)
- Engagement indicators (Active membership, product usage)
- Banking product and card information
- Customer satisfaction metrics

**Target Variable:**  
`Exited` → Indicates whether a customer left the bank.

---

## 🔍 Project Workflow
The project follows an end-to-end ML pipeline:

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training using XGBoost
5. Hyperparameter Tuning using GridSearchCV
6. Model Evaluation
7. Feature Importance Analysis
8. Business Insight Generation

---

## 🤖 Model Used
The final model uses **XGBoost Classifier**, chosen for its strong performance on structured tabular datasets.

Key techniques applied:

- Feature scaling & encoding pipeline
- Hyperparameter tuning
- Early stopping to prevent overfitting
- Class imbalance handling
- Model evaluation using multiple metrics

---

## 📈 Model Performance

| Metric | Score |
|---------|------|
| Accuracy | ~0.79 |
| Precision | ~0.50 |
| Recall | ~0.76 |
| F1 Score | ~0.60 |
| ROC-AUC | ~0.87 |

The model captures most churn cases while maintaining strong overall discrimination ability.

---

## 📌 Key Insights
Important churn drivers discovered:

- Inactive customers churn more frequently.
- Customers using only one product show higher churn risk.
- Middle-aged customers demonstrate higher churn probability.
- Engagement score strongly influences retention.

---

## 📂 Repository Structure
```
bank-customer-churn-prediction/
│
├── bank_customer_churn.ipynb
├── README.md
│
└── data/
    └── README.md
```
