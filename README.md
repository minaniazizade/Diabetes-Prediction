# Diabetes Prediction using Machine Learning 🩺

## Overview
This project aims to predict whether a person is likely to have diabetes or not using Machine Learning classification algorithms.

Several ML models were trained and evaluated to find the best-performing algorithm based on different evaluation metrics.

---

## Dataset
The dataset contains medical information of patients, including features such as:

- Glucose level
- Blood pressure
- BMI
- Age
- Insulin
- Pregnancies
- Skin thickness
- Diabetes pedigree function

The target variable indicates whether the patient has diabetes or not.

link= (https://www.kaggle.com/competitions/playground-series-s5e12/data)

---

## Machine Learning Algorithms Used

The following classification models were implemented:

- Decision Tree
- Random Forest
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gradient Boosting
- XGBoost
- LightGBM
- CatBoost

---

## Model Evaluation

Models were evaluated using:

- Accuracy
- ROC-AUC Score
- F1-Score

### Results
---
![](https://github.com/minaniazizade/Diabetes-Prediction/blob/main/%D8%AA%D8%B5%D9%88%DB%8C%D8%B1%20%D8%B5%D9%81%D8%AD%D9%87%202026-09-23%20182356.png)

---

---
![](https://github.com/minaniazizade/Diabetes-Prediction/blob/main/%D8%AA%D8%B5%D9%88%DB%8C%D8%B1%20%D8%B5%D9%81%D8%AD%D9%87%202026-09-23%20180652.png)
---

## Best Model

🏆 **Gradient Boosting Classifier**

Gradient Boosting achieved the highest F1-score and one of the best ROC-AUC scores among the tested models.

It works by combining multiple weak learners and iteratively correcting previous errors, which helps capture complex patterns in medical data.

---

## Technologies Used

- Excel
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Model Training
6. Model Evaluation
7. Performance Comparison

---
