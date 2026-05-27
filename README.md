# Telecom Customer Churn Prediction using Machine Learning

## Project Overview

This project focuses on predicting customer churn in the telecom industry using machine learning techniques. Customer churn refers to customers discontinuing a company’s services. The objective of this project is to identify customers who are likely to churn based on demographic information, subscription details, service usage, and billing patterns.

The project includes:

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature encoding and scaling
* Machine learning model training
* Model comparison and evaluation
* Customer churn prediction system
* Business insight generation

The final model helps businesses identify high-risk customers and improve customer retention strategies.

---

## Problem Statement

Telecom companies face major revenue loss due to customer churn. Identifying customers who are likely to discontinue services is challenging because churn behavior depends on multiple factors such as tenure, monthly charges, internet services, payment methods, and support services.

The goal of this project is to build a machine learning model capable of predicting customer churn accurately and generating actionable business insights that help companies reduce customer loss and improve retention.

---

## Technologies Used

### Programming Language

* Python

### Libraries & Frameworks

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Pickle

### Machine Learning Models

* Logistic Regression
* Random Forest Classifier
* Support Vector Machine (SVM)
* XGBoost Classifier

### Development Environment

* Jupyter Notebook

---

## Dataset Information

Dataset Used:

* IBM Telco Customer Churn Dataset

Dataset Features Include:

* Customer demographic information
* Service subscription details
* Internet services
* Billing information
* Contract type
* Payment methods
* Churn status

Target Variable:

* Churn

---

## Workflow

### 1. Data Collection

* Imported telecom customer churn dataset.

### 2. Data Cleaning

* Removed unnecessary columns.
* Converted TotalCharges into numeric format.
* Handled missing values.

### 3. Data Preprocessing

* Encoded categorical variables using LabelEncoder.
* Applied feature scaling using StandardScaler.

### 4. Exploratory Data Analysis (EDA)

* Analyzed churn distribution.
* Visualized feature relationships using graphs.
* Identified important churn factors.

### 5. Model Building

Implemented multiple machine learning algorithms:

* Logistic Regression
* Random Forest
* Support Vector Machine (SVM)
* XGBoost

### 6. Model Evaluation

Models were evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

### 7. Prediction System

* Developed a prediction system to classify whether a customer is likely to churn or stay.

### 8. Model Saving

* Saved trained model using Pickle for future deployment.

---

## Results

* Successfully predicted customer churn using machine learning models.
* Logistic regression and Random Forest achieved better prediction accuracy.
* Identified important factors affecting churn such as :
  * Monthly Charges
  * Tenure
  * Contract Type
  * Technical Support
  * Payment Method 

### Key Business Insights

* Customers with month-to-month contracts showed higher churn rates.
* Customers with shorter tenure were more likely to leave.
* High monthly charges increased churn probability.
* Customers without technical support or online security services had higher churn risk.
* Long-term contract customers showed strong retention behavior.

---

# Screenshots

## Dataset overview
<img width="1837" height="599" alt="dataset_overview" src="https://github.com/user-attachments/assets/f4c2785e-8966-43eb-837d-1cdb33ab9d95" />

## Churn Distribution
<img width="687" height="491" alt="churn_distribution" src="https://github.com/user-attachments/assets/fcb4e890-00de-4ca9-be41-d4c3c9b76ded" />

## Accuracy Comparison Chart
<img width="868" height="579" alt="accuracy_comparison" src="https://github.com/user-attachments/assets/ac32a326-cc3a-46db-99d6-312486979d33" />

## Confusion Matrix
<img width="678" height="573" alt="confusion_matrix" src="https://github.com/user-attachments/assets/0d646aa4-5aad-4a8a-bb34-f3ab18ace53d" />

## Feature Importance
<img width="998" height="687" alt="important_features" src="https://github.com/user-attachments/assets/fb6cba2e-d121-4708-ba0f-9eac00e1184d" />

## Prediction Output
<img width="1372" height="430" alt="prediction_output_1" src="https://github.com/user-attachments/assets/33da1a07-b4f0-4806-97e8-5f96b2d0aa75" />


---

## How to Run Project

### Step 1: Clone Repository

```bash
git clone https://github.com/Vrijesh5520/Telco_Customer_Churn_Model.git
```

### Step 2: Open Project Directory

```bash
cd Telcom_Customer_Churn_Model
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

### Step 4: Run Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open Notebook File

Open:

```bash
Telco_Customer_Churn.ipynb
```

### Step 6: Run All Cells

* Train models
* Evaluate performance
* Generate predictions
* Save trained model

---

## Example Prediction

```python
new_customer = pd.DataFrame({
    'gender': [1],
    'SeniorCitizen': [0],
    'Partner': [1],
    'Dependents': [1],
    'tenure': [60],
    'PhoneService': [1],
    'MultipleLines': [1],
    'InternetService': [0],
    'OnlineSecurity': [1],
    'OnlineBackup': [1],
    'DeviceProtection': [1],
    'TechSupport': [1],
    'StreamingTV': [0],
    'StreamingMovies': [0],
    'Contract': [2],
    'PaperlessBilling': [0],
    'PaymentMethod': [1],
    'MonthlyCharges': [45],
    'TotalCharges': [2700]
})
```

Prediction Output:

```python
Customer is likely to STAY
Stay Probability: 0.93
Churn Probability: 0.07
```

---

## Future Improvements

* Deploy project using Streamlit
* Add Hyperparameter Tuning
* Implement SMOTE for class balancing
* Build interactive dashboard

---

# Author
* Vrijesh S. Balam
