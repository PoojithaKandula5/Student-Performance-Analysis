# Student Performance Predictive Model

## Overview

This project aims to predict whether a student will **pass or fail** based on academic performance, attendance, and demographic factors using machine learning techniques.

The model helps identify **at-risk students early**, enabling timely interventions.

---

## Objectives

* Analyze student data (grades, attendance, etc.)
* Perform data cleaning and preprocessing
* Train classification models
* Evaluate model performance
* Identify key factors influencing student success

---

## Technologies Used

* Python
* Pandas & NumPy
* Scikit-learn
* Matplotlib & Seaborn
* Jupyter Notebook
* MS Excel (optional)

---

### Features:

* `study_hours` – Weekly study time
* `attendance` – Attendance percentage
* `assignments_completed` – Number of assignments completed
* `previous_grade` – Previous academic score
* `gender` – Student gender
* `internet_access` – Internet availability
* `pass_fail` – Target variable (0 = Fail, 1 = Pass)

---

## 🔍 Project Workflow

### 1. Data Loading

* Dataset loaded using Pandas

### 2. Data Cleaning

* Handled missing values using forward fill and statistical imputation
* Encoded categorical variables using Label Encoding

### 3. Exploratory Data Analysis (EDA)

* Visualized data distributions
* Used correlation heatmap to identify relationships

### 4. Model Building

Two models were trained:

* Decision Tree Classifier
* Logistic Regression

### 5. Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report

### 6. Feature Importance

* Identified most influential features affecting student performance

---

## Results

* Both models performed well in predicting outcomes
* **Decision Tree** provided better interpretability
* **Attendance and study hours** were the most important features

---

## Key Insights

* Students with higher attendance are more likely to pass
* Study time has a strong positive impact on performance
* Previous academic performance is a reliable predictor
* Demographic factors have relatively lower impact

---

## Future Improvements

* Use advanced models like Random Forest or XGBoost
* Perform hyperparameter tuning
* Deploy the model using Flask or Streamlit
* Use real-world datasets for better generalization

---

## Deliverables

* Jupyter Notebook with full implementation
* Dataset (CSV file)
* Visualizations and performance metrics
* Feature importance analysis

---

## Conclusion

This project demonstrates how machine learning can be used to predict student outcomes and support data-driven decision-making in education.

---
