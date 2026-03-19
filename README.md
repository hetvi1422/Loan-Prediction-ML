# 🏦 Loan Approval Prediction

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-Project-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Model-Logistic%20Regression-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge">
</p>

---

## 📌 Project Overview
This project predicts whether a loan application will be approved or not using Machine Learning techniques.

💡 The model analyzes applicant details like income, education, assets, and financial condition to make predictions.

---

## 🎯 Objective
- Predict loan approval status  
- Understand key factors affecting approval  
- Build a complete ML pipeline  

---

## 🛠️ Tech Stack

| Category        | Tools Used |
|----------------|-----------|
| Language        | Python 🐍 |
| Data Handling   | Pandas, NumPy |
| Visualization   | Matplotlib, Seaborn |
| ML Model        | **Logistic Regression** |
| Library         | Scikit-learn |

---

## 🤖 Model Used

> ✅ **Logistic Regression**

### Why Logistic Regression?
- Simple and effective for classification problems  
- Works well with structured/tabular data  
- Provides interpretable results using coefficients  

---

## 📂 Features Used
- 💰 Income  
- 🎓 Education  
- 🧑‍💼 Self Employment  
- 💳 Loan Amount  
- 🏠 Assets  
- 📊 Credit History  

---

## ⚙️ Project Workflow

```mermaid
graph TD;
    A[Data Collection] --> B[Data Cleaning]
    B --> C[EDA]
    C --> D[Feature Engineering]
    D --> E[Model Training]
    E --> F[Evaluation]
