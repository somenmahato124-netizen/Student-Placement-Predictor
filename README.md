
# 🎓 Student Placement Prediction

A Machine Learning based Student Placement Prediction System that predicts whether a student is likely to be **Placed** or **Not Placed** based on academic and study-related features.

This project demonstrates a complete Data Science and Machine Learning workflow, including data preprocessing, exploratory data analysis, multiple machine learning models, model evaluation, cross-validation, ROC-AUC analysis, threshold analysis, hyperparameter tuning, model saving, and a Streamlit web application.

---

## 📌 Project Overview

The main objective of this project is to develop a Machine Learning model that can predict student placement outcomes based on different academic and study-related factors.

The project follows an end-to-end Machine Learning workflow:

- Data Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Analysis
- Data Preprocessing
- Train-Test Split
- Feature Scaling
- Machine Learning Model Training
- Model Comparison
- Cross Validation
- Classification Report
- Confusion Matrix
- ROC-AUC Analysis
- Class Imbalance Analysis
- Threshold Analysis
- Hyperparameter Tuning
- Final Model Selection
- Model Saving
- New Student Prediction
- Streamlit Application

---

## 🎯 Problem Statement

Student placement can depend on various academic and study-related factors such as study hours, attendance, previous academic performance, assignment completion, sleep hours, and internet usage.

The objective of this project is to use historical student data to predict whether a student is likely to be:

- **Placed**
- **Not Placed**

This project demonstrates how Machine Learning can be applied to educational data and predictive analytics.

---

## 📊 Dataset

The dataset contains student-related academic and study information.

The main features used for prediction are:

| Feature | Description |
|---|---|
| `study_hours` | Average study hours per day |
| `attendance` | Student attendance percentage |
| `sleep_hours` | Average sleep hours per day |
| `internet_usage` | Average internet usage hours per day |
| `assignments_completed` | Number of completed assignments |
| `previous_score` | Previous academic score |

### Target Variable

The target variable represents the student's placement status:

```text
Placed
Not Placed
