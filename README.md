# Credit Risk Scoring System Using Machine Learning

## Executive Summary

Credit risk assessment is one of the most critical processes in banking and financial services. Before approving a loan, financial institutions must evaluate an applicant's ability to repay the borrowed amount while minimizing the risk of default.

This project presents an end-to-end **Credit Risk Scoring System** developed using Machine Learning and the German Credit Dataset. The solution demonstrates how predictive analytics can support lending decisions by classifying applicants into low-risk and high-risk categories based on their financial and demographic characteristics.

The project covers the complete machine learning lifecycle, including data preprocessing, exploratory data analysis (EDA), feature engineering, model development, evaluation, and business interpretation of results. Rather than replacing human judgment, the model is designed as a **decision-support system** that assists financial institutions in making faster, more consistent, and data-driven credit approval decisions.

---

# Business Problem

Loan defaults expose banks and financial institutions to significant financial losses, increased provisioning requirements, and operational risk. Traditional manual credit assessments may be time-consuming and inconsistent, particularly when processing a large number of loan applications.

Financial institutions require intelligent decision-support systems that can evaluate applicants objectively while improving the speed, consistency, and accuracy of credit risk assessment.

---

# Business Objectives

The primary objectives of this project are:

* Develop a machine learning model to classify loan applicants based on credit risk.
* Compare multiple classification algorithms to determine the most suitable model.
* Identify the key factors influencing customer creditworthiness.
* Demonstrate how predictive analytics can improve banking decision-making.
* Showcase the application of machine learning in financial risk management.

---

# Solution Overview

The project implements an end-to-end machine learning workflow that transforms raw customer data into actionable credit risk predictions.

The solution consists of:

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model training
* Model evaluation
* Feature importance analysis
* Business interpretation of results

The final model is intended to support loan officers by providing an additional layer of analytical insight during the credit approval process.

---

# Dataset

**Dataset:** German Credit Dataset

**Source:** UCI Machine Learning Repository

### Dataset Summary

* Total Records: **1000**
* Input Features: **20**
* Target Variable: **Credit Risk**

### Key Features

* Checking Account Status
* Credit History
* Loan Duration
* Credit Amount
* Savings Account Status
* Employment Duration
* Personal Status
* Age
* Housing
* Existing Credits
* Job Category

---

# Project Workflow

```
Loan Applicant Data
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Train-Test Split
        │
        ▼
Model Training
(Logistic Regression & Random Forest)
        │
        ▼
Model Evaluation
        │
        ▼
Feature Importance Analysis
        │
        ▼
Credit Risk Prediction
        │
        ▼
Business Decision Support
```

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

---

# Machine Learning Models

## Logistic Regression

* Accuracy: **75.0%**

### Advantages

* Highly interpretable
* Fast training time
* Suitable for regulated financial environments
* Easy to explain lending decisions

---

## Random Forest

* Accuracy: **73.5%**

### Advantages

* Captures complex relationships
* Robust against overfitting
* Handles non-linear patterns effectively

---

## Model Comparison

| Model               | Accuracy  |
| ------------------- | --------- |
| Logistic Regression | **75.0%** |
| Random Forest       | 73.5%     |

Although Random Forest is a powerful ensemble learning technique, Logistic Regression achieved slightly higher predictive accuracy on this dataset while also providing greater interpretability. In financial institutions, interpretability is often preferred because lending decisions must be transparent and explainable to regulators and customers.

---

# Key Insights

The analysis identified several variables that significantly influence applicant creditworthiness:

* Credit Amount
* Checking Account Status
* Loan Duration
* Age
* Credit History

These findings align with real-world banking practices where financial behaviour, repayment history, and existing liabilities play a major role in determining lending risk.

---

# Results

The project includes the following analyses:

* Credit Risk Distribution
* Credit Amount Distribution
* Applicant Age Distribution
* Correlation Analysis
* Feature Importance Visualization
* Model Performance Comparison

---

# Business Impact

This project demonstrates how machine learning can support financial institutions by:

* Improving consistency in credit risk assessment.
* Assisting loan officers with data-driven decision-making.
* Identifying high-risk applicants before loan approval.
* Supporting portfolio risk management.
* Reducing manual effort in the credit evaluation process.
* Enhancing operational efficiency through predictive analytics.

---

# Repository Structure

```
credit-risk-scoring-system/

├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── credit_risk_analysis.ipynb
│
├── outputs/
│   ├── figures/
│   ├── reports/
│   └── models/
│
├── docs/
│
├── screenshots/
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# Future Enhancements

Future improvements include:

* Address class imbalance using SMOTE.
* Perform hyperparameter optimization.
* Evaluate additional metrics such as ROC-AUC, Precision, Recall, and F1-score.
* Implement advanced ensemble models such as XGBoost and LightGBM.
* Incorporate Explainable AI (SHAP/LIME) for transparent predictions.
* Develop an interactive Streamlit dashboard.
* Deploy the model as a REST API for integration into banking systems.
* Retrain the model using larger and more diverse financial datasets.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/soumilpatro/credit-risk-scoring-system.git
```

Navigate to the project directory:

```bash
cd credit-risk-scoring-system
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook from the `notebooks/` directory.

# Author

**Soumil Patro**

Bachelor of Engineering – Computer Science & Business Systems

Areas of Interest:

* Financial Analytics
* Business Consulting
* Banking Technology
* Machine Learning
* Risk Analytics
