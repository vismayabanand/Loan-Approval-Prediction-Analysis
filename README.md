# 💰 Loan Approval Prediction Analysis

A machine learning project to predict whether a loan application will be approved based on various applicant attributes.

---

## 👥 Authors

- **Vismaya Anand Bolbandi** (862548529)
- **Chandana Anand Rangappa** (862545654)  
- **Ranjitha Narasimhamurthy** (862548883)  

---

## 🧩 Problem Statement

Loan approval is a crucial task for banks and financial institutions. This project aims to build a **predictive model** that can help automate loan approval decisions based on:
- Applicant's demographic information
- Financial standing
- Employment details

> **Goal:** Improve accuracy, consistency, and speed of the loan evaluation process using machine learning.

---

## 📁 Dataset Overview

The dataset includes both **categorical** and **numerical** features relevant to loan applications:

### 🗂️ Categorical Features:
- `person_gender`
- `person_education`
- `person_marital_status`
- `loan_intent`
- `loan_grade`

### 🔢 Numerical Features:
- `person_age`
- `person_income`
- `person_emp_length`
- `loan_amnt`
- `loan_int_rate`
- `cb_person_cred_hist_length`

### 🎯 Target Variable:
- `loan_status` (0 = Denied, 1 = Approved)

---

## 🔍 Analysis & Modeling

The notebook includes the following steps:

1. **Exploratory Data Analysis (EDA)**:
   - Data cleaning
   - Missing value handling
   - Visualizations to understand feature distributions

2. **Preprocessing**:
   - Label encoding for categorical features
   - Feature scaling (if applicable)

3. **Model Training**:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machines (SVM)

4. **Model Evaluation**:
   - Accuracy
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)

5. **Hyperparameter Tuning**:
   - Grid Search or Manual tuning for model improvement

---

## 📈 Results Summary

| Model             | Accuracy |
|------------------|----------|
| Logistic Regression | ~80%   |
| Decision Tree       | ~82%   |
| Random Forest       | ~85%   |
| SVM                 | ~83%   |

> Random Forest performed the best with high generalization capability.

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/loan-approval-prediction.git
   cd loan-approval-prediction
   ```

2. Install the required libraries:
   ```bash
   pip install pandas matplotlib scikit-learn seaborn
   ```

3. Run the notebook:
   ```bash
   jupyter notebook LoanApprovalPredictionAnalysis.ipynb
   ```

---

## 🎯 Key Takeaways

- Predictive modeling can improve efficiency in financial decision-making.
- Handling mixed data types (categorical + numerical) is crucial in real-world datasets.
- Random Forest proved to be a robust model for this task.

---

## 📬 Contact

**Vismaya Anand Bolbandi**  
📧 vbolb001@ucr.edu  
🏫 University of California, Riverside

---
