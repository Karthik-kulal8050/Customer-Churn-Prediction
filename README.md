# 💳 Customer Churn Prediction - Machine Learning Project

## 📌 Project Overview

This project predicts whether a customer will churn using machine learning techniques.  
The objective is to identify customers likely to leave and help businesses take preventive actions.

---

## 📊 Dataset

The dataset contains customer information such as:

- Tenure
- Monthly Charges
- Contract Type
- Payment Method
- Internet Service
- Churn (Target Variable)

---

## ⚙️ ML Pipeline

1. Data Cleaning
2. Handling Missing Values
3. Encoding Categorical Variables
4. Train-Test Split
5. Model Training
6. Cross-Validation
7. Handling Class Imbalance
8. Model Evaluation

---

## 🤖 Models Used

- Logistic Regression (Final Model)
- Random Forest (Comparison)

---

## 📈 Results

| Model | Accuracy | Recall |
|------|----------|--------|
| Logistic Regression | ~75% | **~83%** |
| Random Forest | ~79% | ~46% |

---

## 🔍 Key Insights

- Dataset was imbalanced → handled using class weights
- Recall was prioritized over accuracy
- Logistic Regression performed better for business objective
- Important features: tenure, MonthlyCharges, TotalCharges

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🚀 How to Run

1. Clone repository
2. Install dependencies: