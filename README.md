# 🏥 Hospital Stay Prediction using Machine Learning

## 📌 Project Overview

The **Hospital Stay Prediction** project aims to predict the **length of stay (LOS)** of a patient in a hospital using machine learning techniques. Predicting the duration of hospitalization helps healthcare organizations optimize bed allocation, improve resource planning, reduce operational costs, and enhance patient care.

This project includes complete **Exploratory Data Analysis (EDA)**, **data preprocessing**, **feature engineering**, **machine learning model development**, **hyperparameter tuning**, and **model comparison**.

---

## 🎯 Problem Statement

Hospitals need an efficient way to estimate how long a patient is likely to stay after admission. The prediction is based on patient demographics, hospital information, illness severity, admission type, ward details, and other healthcare-related factors.

The objective is to build a machine learning model that accurately predicts the patient's hospital stay duration.

---

## 🎯 Objectives

* Perform Exploratory Data Analysis (EDA).
* Clean and preprocess the dataset.
* Handle missing values and encode categorical features.
* Build multiple machine learning models.
* Compare model performance.
* Select the best model for prediction.
* Improve model performance using Hyperparameter Tuning.

---

## 📂 Dataset Information

**Domain:** Healthcare

The dataset contains information such as:

* Hospital Type
* Hospital Region
* Department
* Ward Type
* Ward Facility Code
* Bed Grade
* Type of Admission
* Severity of Illness
* Visitors with Patient
* Age
* Admission Deposit
* Stay (Target Variable)

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset Overview
* Missing Value Analysis
* Duplicate Record Analysis
* Target Variable Distribution
* Age Distribution
* Severity of Illness Analysis
* Admission Type Analysis
* Visitors Analysis
* Admission Deposit Distribution
* Correlation Heatmap
* Outlier Detection

---

## ⚙️ Data Preprocessing

* Missing Value Treatment
* Duplicate Value Check
* Label Encoding
* Feature Selection
* Train-Test Split

---

## 🤖 Machine Learning Models

The following classification models were trained and evaluated:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* XGBoost Classifier

---

## 🔧 Hyperparameter Tuning

Hyperparameter tuning was performed using **GridSearchCV** to improve model performance.

Parameters tuned include:

* Number of Estimators
* Maximum Depth
* Minimum Samples Split
* Cross Validation

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

## 📋 Model Comparison

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | XX.XX%   |
| Decision Tree       | XX.XX%   |
| Random Forest       | XX.XX%   |
| XGBoost             | XX.XX%   |

> Replace the values above with your actual results after running the notebook.

---

## 🏆 Best Model

The best-performing model was selected based on overall evaluation metrics.

**Recommended Model:** Random Forest / XGBoost (based on final accuracy and evaluation results)

Reasons:

* High prediction accuracy
* Better generalization
* Reduced overfitting
* Handles nonlinear relationships effectively

---

## 📌 Challenges Faced

* Missing values in important columns
* Handling categorical variables
* Class imbalance in target variable
* Preventing overfitting
* Model selection and optimization

---

## 💡 Suggestions

* Include additional clinical features.
* Perform advanced feature engineering.
* Try CatBoost and LightGBM.
* Deploy the model using Streamlit or Flask.
* Collect more real-world healthcare data.

---

## ✅ Conclusion

This project successfully developed a machine learning solution to predict hospital stay duration. Multiple classification models were trained and evaluated, and the best-performing model was selected based on performance metrics.

The proposed solution can help hospitals improve resource utilization, optimize bed management, support staff planning, and enhance operational efficiency.

---


## 🚀 Future Scope

* Deploy the model as a web application.
* Integrate with hospital management systems.
* Improve prediction accuracy using deep learning.
* Implement real-time patient stay prediction.
* Build an interactive dashboard using Power BI or Streamlit.

---

## 👩‍💻 Author

**Kajal More**

Data Analyst | Machine Learning 

