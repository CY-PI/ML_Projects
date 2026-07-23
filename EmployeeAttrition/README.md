# Employee Attrition Risk Prediction

MVP project for the Machine Learning & Analytics sprint of my postgrad in Data Science and Analytics.

## 🎯 Project Overview

Built a classification model to predict employee attrition risk, using the [IBM HR Analytics dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) (Kaggle).

Since the dataset is imbalanced and the goal was to minimize false negatives, **recall** was chosen as the main metric (target: 70%), with F1-score and ROC-AUC as secondary metrics.

## ✅ Results

I evaluated Logistic Regression, SVM, and XGBoost. **SVM performed best**, reaching **70.2% recall** and **81.1% ROC-AUC**.

**Key driver of attrition:** OverTime, followed by tenure-related features (TotalWorkingYears, YearsAtCompany).

## 🛠️ Tech Stack

Python · pandas · scikit-learn · XGBoost · statsmodels

## ▶️ How to Run

Open `notebook.ipynb` in Google Colab and run all cells — dependencies are installed automatically in the first cell.
