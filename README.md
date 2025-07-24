# 📊 Customer Churn Analysis – Python Project (Databel Telecom)
## 🚀 Project Badges

[![Python](https://img.shields.io/badge/Python-3.9+-blue)](https://www.python.org/)
[![Logistic Regression](https://img.shields.io/badge/Model-Logistic%20Regression-green)](#logistic-regression-model)
[![Accuracy](https://img.shields.io/badge/Accuracy-86.60%25-success)](#logistic-regression-model)
[![Data Rows](https://img.shields.io/badge/Data-6687%20Customers-orange)](#dataset-overview)
[![EDA & Viz](https://img.shields.io/badge/EDA-Matplotlib%20%26%20Seaborn-yellow)](#exploratory-data-analysis-eda)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue)](LICENSE)


This project analyzes customer churn for a fictional telecom company, **Databel**, using Python. It explores key drivers of churn through visualizations and builds a logistic regression model to predict churn behavior.

---

## 📘 Project Overview

Customer churn—the rate at which customers stop doing business with a company—is a major challenge for telecom providers. This project aims to:

- 🔍 **Identify Key Drivers of Customer Churn**  
  Explore demographic, behavioral, and billing factors contributing to churn.

- 📈 **Build a Predictive Model**  
  Use logistic regression to classify churn risk based on customer attributes.

- 💡 **Generate Actionable Insights**  
  Provide recommendations for targeted retention strategies.

---

## ❗ Problem Statement

Telecom providers lose significant revenue due to customer churn. Understanding which customers are at risk—and why—is essential for designing effective retention campaigns.

---

## 📦 Dataset Overview

- **Source**: Simulated dataset from Databel Telecom  
- **Total Records**: 6,687 customers  
- **Features Include**:
  - Demographics: Age, Gender, State, Under 30, Senior  
  - Usage: Local/International Calls & Minutes, Data Usage  
  - Billing: Monthly Charges, Extra Charges, Payment Method  
  - Services: Contract Type, Device Protection, Online Backup  
  - Churn Indicators: Churn Label, Churn Reason, Churn Category

---

## 📊 Exploratory Data Analysis (EDA)

- Checked for null values (only in `Churn Reason`)  
- Calculated churn rate: **~26.5%**  
- Identified top churn reasons and categories  
- Analyzed churn trends by:
  - Account Length  
  - Contract Type  
  - Payment Method  
  - Age & Gender  
  - Data Plans & International Usage  
- Correlation heatmap of numerical features  
- State-wise churn distribution (highest churn in **West Virginia (WV)**)

---

## 📈 Visualizations

- 📊 Bar plot of churn reasons  
- 📉 Line plot comparing churned vs. retained customers by account length  
- 🥧 Pie chart of churn categories  
- 📊 Count plots for categorical features segmented by churn label  
- 🔥 Heatmap of feature correlations  
- 📉 Regression plot of total charges vs. account length by contract type

---

## 🤖 Logistic Regression Model

- **Model**: `LogisticRegression()` from `sklearn`  
- **Features**: One-hot encoded categorical + numerical variables  
- **Train/Test Split**: 50/50  
- **Evaluation Metrics**:
  - Accuracy: **86.60%**  
  - Confusion Matrix  
  - Classification Report

---

## 🛠️ Technologies Used

- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Jupyter Notebook / Kaggle Notebook

---

## 📂 Repository Structure


---

## ✅ Key Insights

- Customers with **month-to-month contracts** churn more frequently  
- **Extra charges** (international/data) are strong churn drivers  
- **Unlimited plan users** show lower churn  
- **Younger and senior customers** are more likely to churn  
- **West Virginia** has the highest churn concentration

---

## 📌 Next Steps

- Try other classification models (Random Forest, XGBoost)  
- Perform feature selection and hyperparameter tuning  
- Deploy model with a dashboard using Streamlit or Flask  
- Integrate with Power BI for hybrid reporting

---

## 👤 Author

**Arun** – Data Analyst  
Skilled in Python, Power BI, Excel, and SQL  
Passionate about storytelling with data and building predictive solutions

---

## 📢 Share & Feedback

If you found this project insightful, feel free to connect or share it on LinkedIn.  
Feedback and collaboration ideas are always welcome!

