# Credit Score Classification – Paisabazaar

## 📊 Project Overview
This project focuses on building a machine learning model to classify customers into **Good**, **Standard**, and **Poor** credit score categories based on their financial and behavioral data.

The objective is to help financial platforms like Paisabazaar improve credit risk assessment and make data-driven lending decisions.

---

## 🎯 Business Problem
Incorrect credit assessment can result in:
- Financial losses due to loan defaults
- Rejection of eligible customers

This project aims to automate and improve credit score classification using machine learning.

---

## 🗂 Dataset Description
The dataset contains customer-level information such as:
- Age
- Annual Income
- Outstanding Debt
- Credit Utilization Ratio
- EMI payments
- Payment behavior
- Credit history

**Target Variable:** `Credit_Score`  
Classes: `Poor`, `Standard`, `Good`

---

## 🧹 Data Preprocessing
- Removed personally identifiable information (ID, Name, SSN)
- Handled missing values using median (numerical) and mode (categorical)
- Converted credit history into numeric format
- Created additional features such as:
  - Debt-to-Income Ratio
  - EMI-to-Salary Ratio
  - Credit Utilization per Card

---

## 📈 Exploratory Data Analysis
- Analyzed credit score distribution using count plots
- Studied relationships using boxplots and violin plots
- Observed that lower credit utilization and manageable debt are associated with good credit scores

---

## 🤖 Model Used
**Random Forest Classifier**

**Why Random Forest?**
- Handles non-linear relationships
- Works well with tabular data
- Reduces overfitting
- Provides feature importance for explainability

---

## 📊 Model Evaluation
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix Heatmap
- Special focus on recall for Poor credit score category

---

## 🔍 Feature Importance
Top influencing features:
- Credit Utilization Ratio
- Outstanding Debt
- Annual Income
- Number of Delayed Payments

---

## ▶️ Project Walkthrough Video
🎥 Copy the Video link
    Paste it and search it on Chrome/edge
    (https://drive.google.com/file/d/1HPtC7WuF0efp0ruBlnppxt6GTjQHtExz/view?usp=drive_link)



---

## 📁 Files in Repository
- `Paisabazaar_Credit_Score_Classification.ipynb` – Colab Notebook
- `README.md` – Project documentation

---

## 🛠 Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn

---

## ✅ Conclusion
This project demonstrates an end-to-end machine learning pipeline for credit score classification and highlights how data-driven models can support financial decision-making in a transparent and scalable manner.
