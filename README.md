# Heart Disease Prediction using Machine Learning

## Overview

Heart disease remains one of the leading causes of death worldwide, making early diagnosis critical for improving patient survival rates. This project focuses on predicting the likelihood of heart disease using machine learning models trained on structured healthcare data.

The objective is to analyze patient health metrics, identify patterns associated with heart disease, and compare multiple machine learning models to determine the most effective prediction system.

This project demonstrates practical skills in data preprocessing, feature engineering, model training, evaluation, and healthcare data analysis.

---

## Problem Statement

Traditional heart disease diagnosis can be time-consuming and dependent on multiple medical tests. Delayed identification increases health risks and treatment complexity.

This project aims to:

* Predict heart disease presence based on patient health parameters
* Analyze important contributing factors
* Compare machine learning algorithms for performance optimization
* Build a scalable foundation for future healthcare prediction systems

---

## Dataset Information

The dataset used in this project is sourced from Kaggle public healthcare records.

### Dataset Summary

* **Total Records:** 918
* **Target Variable:** `HeartDisease`
* **Binary Classification:**

  * `0` → No Heart Disease
  * `1` → Heart Disease

### Features Used

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise Angina
* Oldpeak
* ST Slope

---

## Tech Stack

### Programming Language

* Python

### Libraries Used

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

### Machine Learning Models

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest
* Gradient Boosting

---

## Project Workflow

### 1. Data Preprocessing

To improve model performance and ensure consistency:

* Cleaned missing and inconsistent values
* Encoded categorical variables into numerical format
* Scaled numerical features using standard normalization
* Split data into train and test sets

### 2. Feature Analysis

Performed correlation analysis to identify important predictors.

Strong influencing features:

* ST_Slope
* Oldpeak
* ChestPainType
* MaxHR
* Cholesterol

This helped improve interpretability and understand feature importance.

---

## Model Training

The dataset was split using stratified sampling to maintain class balance.

### Split Ratio

* Training Set: 642 records
* Validation Set: 138 records
* Test Set: 138 records

### Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

---

## Model Performance

| Model                  | Accuracy |
| ---------------------- | -------- |
| Logistic Regression    | 90.6%    |
| Support Vector Machine | 91.3%    |
| Random Forest          | 89.9%    |
| Gradient Boosting      | 90.6%    |

### Best Performing Model

**Support Vector Machine (SVM)** achieved the highest validation accuracy of **91.3%**, making it the most reliable model in this project.

---

## Results & Insights

* Machine learning successfully predicted heart disease with over **90% accuracy**
* SVM showed strong classification capability on this dataset
* Feature correlation helped identify major health indicators
* The project demonstrates the effectiveness of predictive analytics in healthcare

---

## Limitations

Despite strong performance, some limitations exist:

* Small dataset size (918 records)
* Limited data diversity
* No real-world clinical validation
* Potential dataset bias

---

## Future Improvements

To strengthen the model further:

* Use larger real-world medical datasets
* Apply advanced hyperparameter tuning
* Experiment with deep learning models
* Deploy as a real-time web dashboard
* Integrate patient history and wearable device data

---

## Key Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning Model Building
* Model Evaluation
* Healthcare Analytics
* Predictive Modeling

---

## Conclusion

This project demonstrates how machine learning can support early heart disease detection by analyzing patient health data efficiently. By comparing multiple models, the system identified SVM as the best-performing model, proving that predictive healthcare systems can assist medical professionals in making faster and more accurate decisions.


