# Telco Customer Churn Prediction

An end-to-end Machine Learning project that predicts whether a telecom customer is likely to churn and provides actionable insights to support customer retention.

## 🎯 Business Problem

Customer churn occurs when a customer leaves a service.

The key business question is:

> **Which customers are likely to churn, and how can the business prioritize retention efforts?**

Accurately identifying potential churners can help businesses take proactive retention actions.

- **False Positive:** Retention effort is spent on a customer who would not have churned.
- **False Negative:** A potential churner is missed, resulting in a lost customer.

Therefore, model evaluation considers multiple classification metrics rather than accuracy alone.

---

## 📊 Project Objective

The project follows an end-to-end Machine Learning workflow:

1. Business Understanding
2. Data Understanding
3. Data Quality Checks
4. Exploratory Data Analysis
5. Feature & Target Definition
6. Train-Test Split
7. Data Preprocessing
8. Logistic Regression
9. Model Evaluation
10. Model Comparison
11. Model Interpretation
12. Final Model Selection
13. Model Serialization
14. Prediction Application
15. Application Testing
16. Local Application Launcher

---

## 🔍 Exploratory Data Analysis

The dataset was explored to understand:

- Customer demographics
- Service subscriptions
- Contract types
- Payment methods
- Tenure
- Monthly charges
- Total charges
- Churn distribution
- Relationships between customer characteristics and churn

The analysis focused on identifying patterns and associations that can help explain customer churn behavior.

---

## 🤖 Machine Learning Models

The following classification models were developed and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Models were compared using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

Special attention was given to **Recall and F1-Score**, since missing a customer who is likely to churn can have a direct business impact.

---

## 🧠 Model Interpretation

Feature importance and model behavior were analyzed to understand which customer characteristics contribute most to churn prediction.

This helps connect the Machine Learning results with practical business decision-making.

---

## 🚀 Prediction Application

A prediction application was developed using **Python and Gradio**.

The application allows users to enter customer information and receive:

- Churn prediction
- Churn probability
- Recommended retention action

The trained Machine Learning pipeline is saved as:

`telco_churn_model.pkl`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Gradio
- Joblib
- Jupyter Notebook

---

## 📁 Repository Structure

```text
Telco-Customer-Churn-Prediction/
│
├── Documentation/
│
├── TELCO CUSTOMER CHURN ML MODEL.ipynb
│
├── app.py
├── run_app.bat
├── telco_churn_model.pkl
├── .gitignore
└── README.md
