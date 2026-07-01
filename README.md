# 🏦 Loan Approval Prediction using Machine Learning

## 📌 Project Overview

This project builds machine learning models to predict whether a loan application will be approved based on applicant information. The workflow includes data preprocessing, handling missing values, class balancing using SMOTE, model training, evaluation, and comparison of multiple algorithms.

---

## 🎯 Objectives

- Predict loan approval status.
- Handle missing values.
- Encode categorical variables.
- Scale numerical features.
- Balance the dataset using SMOTE.
- Compare multiple machine learning models.
- Evaluate model performance.

---

## 📂 Dataset

The dataset contains **614 loan applications** with **13 features**.

### Features

- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)

---

## 📊 Project Workflow

1. Import libraries
2. Load dataset
3. Data exploration
4. Handle missing values
5. Feature preprocessing
6. Train-test split
7. Apply SMOTE
8. Train models
9. Evaluate performance
10. Compare models

---

## 🤖 Machine Learning Models

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 📊 Results

| Model | ROC-AUC |
|--------|---------|
| Logistic Regression | **0.8687** |
| Random Forest | 0.7986 |
| XGBoost | 0.7845 |

**Best Model:** Logistic Regression

---

## 📷 Visualizations

- Missing Values Analysis
- Target Distribution
- ROC Curve Comparison
- Confusion Matrix
- Feature Importance Plot

---

## 💡 Key Insights

- Missing values were handled successfully.
- SMOTE balanced the training dataset.
- Logistic Regression achieved the highest ROC-AUC score.
- Credit history is one of the most important factors in loan approval.

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/yourusername/Loan-Approval-Prediction.git
```

2. Install dependencies.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
```

3. Open the notebook in Google Colab or Jupyter Notebook.

4. Run all cells sequentially.

---

## 📁 Project Structure

```
Loan-Approval-Prediction/
│
├── loan_prediction.csv
├── loan_prediction.ipynb
├── report.pdf
├── README.md
└── images/
```

---
