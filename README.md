
# **Credit Card Fraud Transactions**

## **Objective**
This project aims to build a model to predict whether a transaction is fraudulent. We will also evaluate different models to determine which works best for this type of dataset.

---

## **Contents**
1. Introduction
2. Dataset
3. Analysis
4. Models
5. Results
6. Conclusion
7. References

---

## **1. Introduction**
Credit card usage worldwide reached 2.8 billion users in 2019, with 70% owning at least one card. Unfortunately, credit card fraud has increased significantly:
- Reports of fraud in the U.S. rose 44.7% from 271,927 in 2019 to 393,207 in 2020.
- Two types of fraud:
  - **Identity Theft**: A thief opens a credit card in someone else’s name (48% increase from 2019 to 2020).
  - **Account Takeover**: A thief uses an existing account (9% increase from 2019 to 2020).

Given these alarming statistics, this project aims to explore machine learning models to detect fraudulent transactions. The goal is to identify and compare various models, focusing on their effectiveness for our dataset.

As a Data Scientist working in FinTech, I’ve observed the complexity of identifying fraud. Fraudsters constantly innovate to bypass detection, making it essential to develop accurate and robust models. While many fraud detection solutions already exist, this project aims to consolidate and evaluate multiple approaches to identify the best one for this dataset.

In FinTech, regulatory requirements often favor interpretable models over black-box algorithms. Hence, this project focuses on models like **K-Nearest Neighbors (KNN)**, **Support Vector Machines (SVM)**, and **Logistic Regression**, avoiding black-box methods to ensure interpretability and compliance.

---

## **2. Dataset**
- **Source**: [Kaggle Dataset]
- **Description**: A simulated dataset containing legitimate and fraudulent transactions from January 1, 2019, to December 31, 2020.
- **Scope**:
  - Credit card transactions from 1,000 customers across 800 merchants.
- **Columns**:
  - Full List: ['Unnamed: 0', 'trans_date_trans_time', 'cc_num', 'merchant', 'category', 'amt', 'first', 'last', 'gender', 'street', 'city', 'state', 'zip', 'lat', 'long', 'city_pop', 'job', 'dob', 'trans_num', 'unix_time', 'merch_lat', 'merch_long', 'is_fraud']
  - Relevant Columns: ['trans_date_trans_time', 'cc_num', 'amt', 'merchant', 'category', 'is_fraud']

---

## **3. Analysis**
- **Total Transactions**: 1,842,743 (legitimate) + 9,651 (fraudulent)
- **Fraudulent Transactions Percentage**: 0.52%
- This dataset is **highly imbalanced**, which will influence model selection and evaluation.

---

## **4. Models**
The following models will be implemented and compared:
1. **K-Nearest Neighbors (KNN)**
2. **Support Vector Machines (SVM)**
3. **Logistic Regression**
4. Other advanced models (e.g., Random Forest, Gradient Boosting)

---

## **5. Results**
*Detailed results and evaluation metrics for each model will be documented here.*

---

## **6. Conclusion**
This section will summarize the findings, highlighting the most effective model for detecting fraudulent transactions based on interpretability, accuracy, and compliance considerations.

---

## **7. References**
- Daly, J. (2021). *Credit Card Fraud Statistics 2021.*
- [Kaggle Dataset Link]
