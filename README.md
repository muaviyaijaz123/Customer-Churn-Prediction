# Customer Churn Prediction

This repository contains the implementation of a Customer Churn Prediction model for a bank, conducted as part of the [Condor Student Challenge](#). The project predicts whether a customer will close their bank account (`Exited`) based on various customer attributes.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Installation](#installation)
---

## Introduction
Customer churn prediction is crucial for banks to retain customers and optimize marketing efforts. In this challenge, the goal was to:
1. **Model customer churn** using the provided dataset.
2. Perform **data analysis, pre-processing, model development, and evaluation**.
3. Showcase technical knowledge and present key insights.

---

## Dataset
The dataset comprises two CSV files:
- **data_train.csv**: Training dataset with customer details and the target variable (`Exited`).
- **data_test.csv**: Test dataset for evaluating the model.

### Columns:
- `CreditScore`: Credit score of the customer.
- `Geography`: The country from which the customer belongs.
- `Gender`: Male or Female.
- `Age`: Age of the customer.
- `Tenure`: Number of years with the bank.
- `Balance`: Bank balance of the customer.
- `NumOfProducts`: Number of bank products utilized.
- `HasCrCard`: Whether the customer has a credit card.
- `IsActiveMember`: Whether the customer is an active member.
- `EstimatedSalary`: Estimated salary of the customer.
- `Exited`: Target variable (1 = churned, 0 = retained).
- `PostExitQuestionnaire`: Binary flag if a questionnaire was distributed to the
customer after exiting

---

## Project Workflow
1. **Exploratory Data Analysis (EDA)**:
   - Visualized trends, distributions, and correlations.
   - Highlighted key churn indicators.
2. **Data Pre-processing**:
   - Handled missing values, encoded categorical variables, and normalized numerical features.
3. **Model Development**:
   - Implemented multiple machine learning models (e.g., Logistic Regression, Random Forest, Gradient Boosting).
   - Tuned hyperparameters for optimal performance.
4. **Evaluation**:
   - Assessed models using metrics like accuracy, precision, recall, F1-score, and AUC-ROC.
   - Selected the best-performing model for deployment.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/muaviyaijaz123/customer-churn-prediction.git
   cd customer-churn-prediction
