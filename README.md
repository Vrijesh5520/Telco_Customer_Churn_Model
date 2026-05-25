# Telco_Customer_Churn_Model
Developed a machine learning-based customer churn prediction system using telecom customer data to identify customers likely to discontinue services.

# Project Overview

This project focuses on predicting customer churn in the telecom industry using machine learning techniques. Customer churn refers to customers discontinuing a company’s services. The objective of this project is to identify customers who are likely to churn based on demographic information, subscription details, service usage, and billing patterns.

The project includes:

Data preprocessing and cleaning
Exploratory Data Analysis (EDA)
Feature encoding and scaling
Machine learning model training
Model comparison and evaluation
Customer churn prediction system
Business insight generation

The final model helps businesses identify high-risk customers and improve customer retention strategies.

# Problem Statement

Telecom companies face major revenue loss due to customer churn. Identifying customers who are likely to discontinue services is challenging because churn behavior depends on multiple factors such as tenure, monthly charges, internet services, payment methods, and support services.

The goal of this project is to build a machine learning model capable of predicting customer churn accurately and generating actionable business insights that help companies reduce customer loss and improve retention.

# Technologies Used :

Programming Language - Python
Libraries & Frameworks - Pandas , NumPy , Matplotlib , Seaborn , Scikit-learn , XGBoost , Pickle
Machine Learning Models - Logistic Regression , Random Forest Classifier , Support Vector Machine (SVM) , XGBoost Classifier
Development Environment - Jupyter Notebook

# Dataset Information

Dataset Used : IBM Telco Customer Churn Dataset

Dataset Features Include:
1. Customer demographic information
2. Service subscription details
3. Internet services
4. Billing information
5. Contract type
6. Payment methods
7. Churn status

Target Variable : Churn

# Workflow
1. Data Collection :-
Imported telecom customer churn dataset.

2. Data Cleaning :-
Removed unnecessary columns.
Converted TotalCharges into numeric format.
Handled missing values.

3. Data Preprocessing :-
Encoded categorical variables using LabelEncoder.
Applied feature scaling using StandardScaler.

4. Exploratory Data Analysis (EDA) :-
Analyzed churn distribution.
Visualized feature relationships using graphs.
Identified important churn factors.

5. Model Building :-
Implemented multiple machine learning algorithms :
  Logistic Regression
  Random Forest
  Support Vector Machine (SVM)
  XGBoost

6. Model Evaluation :-
Models were evaluated using :
  Accuracy Score
  Classification Report
  Confusion Matrix

7. Prediction System :-
Developed a prediction system to classify whether a customer is likely to churn or stay.

8. Model Saving :-
Saved trained model using Pickle for future deployment.

# Results
Model Performance : 
  Achieved strong prediction accuracy using ensemble models such as Random Forest and XGBoost.
  Random Forest performed effectively for feature importance analysis.

# Key Business Insights
1. Customers with month-to-month contracts showed higher churn rates.
2. Customers with shorter tenure were more likely to leave.
3. High monthly charges increased churn probability.
4. Customers without technical support or online security services had higher churn risk.
5. Long-term contract customers showed strong retention behavior.

# Business Value
1. Helps businesses identify high-risk customers.
2. Enables targeted retention campaigns.
3. Improves customer satisfaction and retention.
4. Reduces revenue loss due to customer churn.

# Screenshots
Add screenshots of the following:
Dataset Overview
Churn Distribution Graph
Correlation Heatmap
Confusion Matrix
Model Accuracy Comparison
Feature Importance Graph
Prediction Output


# Project Structure
customer-churn-prediction/ │ ├── Telco_Customer_Churn_(ML).ipynb ├── requirements.txt ├── README.md ├── model.pkl ├── scaler.pkl ├── screenshots/ └── dataset/

# How to Run Project
Step 1: Clone Repository
git clone <your-github-repository-link>
Step 2: Open Project Directory
cd customer-churn-prediction
Step 3: Install Required Libraries
pip install -r requirements.txt
Step 4: Run Jupyter Notebook
jupyter notebook
Step 5: Open Notebook File
Open >> Telco_Customer_Churn.ipynb
Step 6: Run All Cells
 Train models
 Evaluate performance
 Generate predictions
 Save trained model
