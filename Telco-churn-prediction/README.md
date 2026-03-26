# 📉 Telco Customer Churn Prediction

This project focuses on building Machine Learning models to predict customer churn in a telecommunications company.

Customer churn prediction helps telecom companies identify customers who are likely to leave their service, enabling proactive retention strategies.

## 🚀 Project Objective

The main goal of this project is to:

    Predict whether a customer will churn or stay based on their subscription behavior, service usage, and account information.

This enables:

    1. arly identification of at-risk customers
    2. Targeted retention campaigns
    3. Revenue protection
    4. Customer experience improvement

## 🧠 Problem Type
- Machine Learning Task: Binary Classification

- Target Variable: Churn

- Classes:
    Yes (Customer will churn)
    No (Customer will stay)

- Primary Evaluation Focus:
    ⭐ Recall Score for Churn Class

Since missing a churn customer is costly, the model prioritizes correctly identifying customers who are likely to leave.

## 📊 Dataset Description

The dataset contains customer-level information including:

    1. Demographics (gender, senior citizen status, partner, dependents)
    2. Account information (tenure, contract type, billing method)
    3. Services subscribed (internet service, online security, tech support, etc.)
    4. Financial information (monthly charges, total charges)

## 🔎 Exploratory Data Analysis Highlights

Key insights discovered during analysis:

#### 📅 Contract Type Impact

Customers on month-to-month contracts show significantly higher churn rates compared to long-term contracts.

#### 💻 Service Usage Influence

Customers without:

    Online Security
    Tech Support
    Online Backup

are more likely to churn.

#### 💰 Pricing Behavior

Higher monthly charges correlate with increased churn probability, especially among newer customers.

#### ⏳ Customer Tenure

Customers with shorter tenure are significantly more likely to churn.

## ⚙️ Machine Learning Workflow

The project follows a structured pipeline:

1. Data Cleaning
2. Handling Missing Values
3. Encoding Categorical Variables
4. Feature Engineering
5. Model Training
6. Hyperparameter Optimization
7. Model Evaluation
8. Prediction Analysis