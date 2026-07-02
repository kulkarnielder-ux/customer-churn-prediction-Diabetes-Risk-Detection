# 🚀 Machine Learning Portfolio Projects

This repository contains end-to-end machine learning projects demonstrating skills in data preprocessing, predictive analytics, model evaluation, visualization, and ethical AI practices. These projects were developed as part of a portfolio focused on Data Analytics, Machine Learning, and Predictive Modeling.

---

# 📊 Project 1: Customer Churn Prediction Pipeline

## Project Overview

This project develops a predictive analytics pipeline to identify customers at risk of leaving a telecom service provider. Multiple machine learning classification models were evaluated to determine the most effective approach for customer retention analysis.

## Dataset

* Dataset Type: Synthetic Telecom Customer Dataset
* Number of records: 5,000 customers
* Objective: Predict customer churn
* Target Variable: Churn (Yes/No)

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Methodology

### 1. Data Generation

A synthetic telecom dataset was created containing:

* Customer tenure
* Monthly charges
* Contract types
* Payment methods
* Technical support
* Internet services
* Customer demographics

### 2. Data Preprocessing

* Label encoding of categorical variables
* Feature engineering
* Train-test split
* Feature scaling for linear models

### 3. Machine Learning Models

The following classification algorithms were implemented:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

### 4. Model Evaluation

Performance metrics used:

* Accuracy
* Recall
* ROC-AUC Score
* 5-Fold Cross Validation ROC-AUC
* Classification Report
* Confusion Matrix

### 5. Visualization

ROC curves were generated to compare model performance and identify the best predictive model.

## Key Findings

Important churn indicators included:

* Contract type
* Monthly charges
* Customer tenure
* Technical support availability
* Online security services
* Payment methods

## Future Improvements

* Hyperparameter tuning
* Feature selection
* XGBoost and LightGBM implementation
* Customer segmentation analysis
* Model deployment using Flask or Streamlit

---

# 🩺 Project 2: Diabetes Risk Prediction Using Machine Learning

## Project Overview

This project develops a predictive analytics pipeline to detect diabetes risk using diagnostic medical measurements from the Pima Indians Diabetes Dataset. The objective is to assist healthcare professionals by identifying high-risk patients through machine learning techniques.

## Dataset

* Dataset: Pima Indians Diabetes Dataset (UCI Machine Learning Repository)
* Number of records: 768
* Features: 8 diagnostic measurements
* Target: Diabetes outcome (Positive/Negative)

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Methodology

### 1. Data Acquisition

The Pima Indians Diabetes dataset was imported directly from a public repository.

### 2. Data Preprocessing

* Missing medical values represented by zeros were replaced with NaN values
* Median imputation was applied
* Feature normalization was performed using StandardScaler

### 3. Model Development

A Random Forest Classifier was implemented to predict diabetes risk.

### 4. Model Evaluation

Performance metrics used:

* Classification Report
* Precision
* Recall
* F1-Score
* ROC-AUC Score

### 5. Feature Importance Analysis

Feature importance scores were calculated to identify key risk factors influencing diabetes prediction.

## Key Findings

The model identified important predictors such as:

* Glucose Level
* BMI
* Age
* Diabetes Pedigree Function
* Insulin Levels

## Ethical Considerations

* Patient data anonymization
* Informed consent requirements
* Bias mitigation strategies
* Healthcare data security and privacy compliance

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Explainable AI (SHAP/LIME)
* Deep learning approaches
* Deployment using Flask/Streamlit

---

# 📈 Skills Demonstrated

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning Classification
* Model Evaluation and Validation
* Cross Validation
* Data Visualization
* Predictive Analytics
* Feature Importance Analysis
* Ethical AI and Responsible Data Science

---

## 🛠 Tools & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

---

## 👨‍💻 Author

**Omkar Kulkarni**

This repository was developed as part of a Machine Learning and Data Analytics portfolio to demonstrate practical applications of predictive analytics in business and healthcare domains.
