# 📊 Customer Churn Analysis – Python Project (Databel Telecom)

## 🚀 Project Badges

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/) [![Model–Logistic Regression](https://img.shields.io/badge/Model-Logistic%20Regression-green)](#logistic-regression-model) [![Accuracy–86.60%](https://img.shields.io/badge/Accuracy-86.60%25-success)](#logistic-regression-model) [![Data–6,687_Customers](https://img.shields.io/badge/Data-6%2C687_Customers-orange)](#dataset-overview) [![EDA–Matplotlib %26 Seaborn](https://img.shields.io/badge/EDA-Matplotlib%20%26%20Seaborn-yellow)](#exploratory-data-analysis-eda) [![License–MIT](https://img.shields.io/badge/License-MIT-blue)](LICENSE)


---

## 📘 Project Overview

This repository hosts a Python‐based analysis of customer churn for **Databel Telecom**. We explore why customers leave, visualize key patterns, and build a logistic regression model to predict churn risk.

**Objectives:**
- 🔍 Identify key drivers of customer churn  
- 📈 Build a predictive logistic regression model  
- 💡 Deliver actionable recommendations for retention strategies  

---

## ❗ Problem Statement

High churn rates erode revenue and growth. Telecom providers must understand which customers are at risk and why, to tailor retention efforts and reduce attrition.

**Key Questions:**
- Which customer segments show the highest churn?  
- How do contract type, usage, and billing behaviors influence churn?  
- Can we predict churn with sufficient accuracy to intervene proactively?  

---

## 📦 Dataset Overview

- **Rows:** 6,687 customer records  
- **Columns (29):**  
  - Demographics: Customer ID, Age, Gender, State, Under 30, Senior  
  - Usage: Account Length, Local/Intl Calls & Minutes, Data Usage  
  - Billing: Monthly Charges, Extra Charges, Payment Method  
  - Services: Contract Type, Device Protection & Online Backup, Intl Plan, Unlimited Data Plan  
  - Churn: Churn Label, Churn Category, Churn Reason  

---

## 📊 Exploratory Data Analysis (EDA)

- Checked for nulls (only in `Churn Reason`)  
- Overall churn rate: **26.86%**  
- Top churn reasons: Competitor offers, device issues, support attitude  
- Churn vs. account length trends  
- Categorical breakdown by contract, payment, gender, plans  
- Correlation heatmap to identify related features  
- State-level churn hotspots (highest in West Virginia)

---

## 📐 Notebook Preview

Click any thumbnail to view the full page:

| Page | Preview |
|:----:|:-------:|
| 1  | ![Page 1](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_1.png) |
| 2  | ![Page 2](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_2.png) |
| 3  | ![Page 3](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_3.png) |
| 4  | ![Page 4](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_4.png) |
| 5  | ![Page 5](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_5.png) |
| 6  | ![Page 6](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_6.png) |
| 7  | ![Page 7](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_7.png) |
| 8  | ![Page 8](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_8.png) |
| 9  | ![Page 9](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_9.png) |
| 10 | ![Page 10](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_10.png) |
| 11 | ![Page 11](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_11.png) |
| 12 | ![Page 12](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_12.png) |
| 13 | ![Page 13](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_13.png) |
| 14 | ![Page 14](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_14.png) |
| 15 | ![Page 15](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_15.png) |
| 16 | ![Page 16](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_16.png) |
| 17 | ![Page 17](https://github.com/data-wizard-AKP/customer-churn-analysis-python-databel/blob/main/Python_code/page_17.png) |

---

## 🤖 Logistic Regression Model

We built and evaluated a logistic regression classifier:

- **Train/Test Split:** 50/50  
- **Accuracy:** 86.60%  
- **Key Metrics:**  
  - Precision/Recall/F1 for both classes  
  - Confusion matrix  

---

## 🛠️ Tools & Technologies

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/) [![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/) [![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/) [![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/) [![Seaborn](https://img.shields.io/badge/Seaborn-77AADD?style=for-the-badge&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/) [![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/) [![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)


---

## 📌 Next Steps

- Experiment with advanced classifiers (Random Forest, XGBoost)  
- Feature selection & hyperparameter tuning  
- Deploy as a web app (Streamlit/Flask)  
- Integrate with Power BI for hybrid dashboards  

---

## 👤 Author

<p align="center">
  <img src="https://raw.githubusercontent.com/data-wizard-AKP/customer-churn-analysis-python-databel/main/Python_code/Arun.jpeg" alt="Arun" width="120" style="border-radius:50%;" />
</p>

<p align="center">
  <strong>Arun</strong> – Data Analyst<br/>
  • Power BI, Python, SQL & Excel<br/>
  • Crafting data stories & predictive solutions
</p>

---

## 📢 Share & Feedback

Enjoyed this analysis? Please ⭐ the repo, drop feedback, or connect via LinkedIn to discuss collaboration!  


