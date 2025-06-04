# 📊 Customer Churn Prediction using Machine Learning

This project involves building a machine learning model to predict customer churn based on demographic, transactional, and behavioral data. The goal is to help the business identify customers who are likely to leave and take proactive retention actions.

---

## 🔍 Problem Statement

Customer churn is a critical challenge for businesses. Retaining existing customers is often more cost-effective than acquiring new ones. By predicting which customers are at risk of churning, the business can intervene early with targeted strategies.

---

## 🧠 Solution Approach

- Exploratory Data Analysis (EDA)
- Data preprocessing (encoding categorical variables, handling class imbalance)
- Model building using:
  - **Logistic Regression** (baseline)
  - ✅ **Random Forest Classifier** (final selected model)
- Model evaluation using metrics like **Accuracy, Precision, Recall, F1-Score, and Confusion Matrix**
- Business recommendation based on model outputs

---

## 📁 Dataset

The dataset includes the following files:

- `Customer_Demographics.csv`
- `Transaction_History.csv`
- `Customer_Service_Interactions.csv`
- `Online_Activity.csv`
- `Churn_Status.csv`

The final dataset was merged and preprocessed to create a clean input for model training.

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📈 Model Performance (Random Forest Classifier)

- **Accuracy**: 98.75%
- **Precision (Churned Customers)**: 100%
- **Recall (Churned Customers)**: 94%
- **F1-Score (Churned Customers)**: 0.97
- **Confusion Matrix**:[[826 0] [ 13 202]]
---

## 💼 Business Impact

- Helps marketing team identify at-risk customers.
- Enables targeted retention campaigns.
- Can reduce revenue loss from customer churn.
- Supports data-driven decision making in CRM strategy.

---

## 🚀 Future Improvements

- Hyperparameter tuning with GridSearchCV
- Use SMOTE or Balanced Bagging to improve minority class recall
- Add behavioral and temporal features
- Model deployment using Flask or Streamlit

---
