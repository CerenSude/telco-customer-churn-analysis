# 📊 Telco Customer Churn Prediction

## 📌 Overview
This project analyzes the **Telco Customer Churn dataset** to identify factors that influence customer churn and build predictive models to classify customers who are likely to leave.  
The goal is to provide insights that help telecom companies **improve customer retention** through data-driven decision-making.

---

## ⚙️ Workflow
✅ **Data Loading & Cleaning** – Imported the dataset, handled missing values, and corrected data types.  
✅ **Feature Identification** – Differentiated categorical and numerical variables.  
✅ **Exploratory Data Analysis (EDA)** – Visualized distributions, relationships, and churn trends.  
✅ **Data Preprocessing** – Encoded categorical features, scaled numeric data, and split into train/test sets.  
✅ **Model Building** – Implemented Logistic Regression, Decision Tree, Random Forest, and SVM models.  
✅ **Model Evaluation** – Compared model performance using Accuracy, Precision, Recall, F1, and ROC-AUC.  
✅ **Feature Importance** – Interpreted key variables that drive churn behavior.

---

## 🧠 Key Findings
- **Random Forest** achieved the best overall performance, showing strong balance across all metrics.  
- **Logistic Regression** achieved the highest recall, making it most effective for detecting churners.  
- **Tenure**, **Contract Type**, and **Internet Service Type** were the top predictors of churn.  
- Customers with **month-to-month contracts** and **Fiber Optic Internet without tech support** had the highest churn probability.

---

## 🗂 Dataset
The dataset used is the [**Telco Customer Churn Dataset**](https://www.kaggle.com/blastchar/telco-customer-churn) from Kaggle.  
It includes customer demographics, account information, and service usage details from a telecom company.
