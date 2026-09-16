# Customer Churn Prediction

A Machine Learning project that predicts whether a customer is likely to leave (churn) a company based on their demographic and account information.

## 📌 Project Overview

Customer churn is an important problem for businesses because retaining existing customers is often more beneficial than acquiring new ones.

In this project, a customer churn prediction model is developed using customer information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card Status
- Active Membership
- Estimated Salary

The project includes data preprocessing, exploratory data analysis, feature engineering, model building, and evaluation.

## 📂 Dataset

The dataset contains customer information along with a target variable indicating whether the customer has exited the company.

### Important Features

| Feature | Description |
|---|---|
| CreditScore | Customer's credit score |
| Geography | Customer's country |
| Gender | Customer's gender |
| Age | Customer's age |
| Tenure | Number of years the customer has been with the company |
| Balance | Customer's account balance |
| NumOfProducts | Number of products used by the customer |
| HasCrCard | Whether the customer has a credit card |
| IsActiveMember | Whether the customer is an active member |
| EstimatedSalary | Customer's estimated salary |
| Exited | Target variable indicating churn |

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras
- Jupyter Notebook

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Encoding Categorical Variables
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Neural Network Model
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Customer Churn Prediction
