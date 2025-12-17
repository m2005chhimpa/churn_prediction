# churn_prediction
An end to end business intelligence solution analyzing customer attrition. Leverages python for data cleaning and power bi for visualizing retention strategies.

# 📉 Customer Churn Prediction & Analytics Dashboard

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-yellow)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Project Overview
This project focuses on analyzing customer attrition (churn) within the telecommunications industry. By leveraging Python for data processing and Machine Learning, and Power BI for interactive visualization, this solution identifies key indicators of customer churn and provides actionable strategies to improve retention.

The goal is to answer two critical business questions:
1. *Who* is leaving? (Demographics & Service patterns)
2. *Why* are they leaving? (Churn Drivers)

## 🛠 Tech Stack
* *Data Processing:* Python (Pandas, NumPy)
* *Machine Learning:* Scikit-Learn (Logistic Regression/Random Forest)
* *Visualization:* Power BI (DAX, Data Modeling), Matplotlib/Seaborn
* *Environment:* Jupyter Notebook / Google Colab

## 📊 Dataset Description
The dataset includes customer demographics, account information, and subscription services.
* *Target Variable:* Churn (Yes/No)
* *Key Features:* Tenure, Contract, MonthlyCharges, TotalCharges, TechSupport, InternetService.

## 🖥 The Power BI Dashboard
(Place a screenshot of your Power BI dashboard here)

*Dashboard Features:*
* *KPI Tracking:* Real-time view of Churn Rate, Revenue Lost, and Average Tenure.
* *Cohort Analysis:* Breakdown of churn by Contract Type and Payment Method.
* *Service Impact:* Visualizing how technical support and streaming services affect loyalty.

## 🚀 Key Insights
* *Contract Sensitivity:* Customers on "Month-to-month" contracts have a significantly higher churn rate compared to 1 or 2-year contracts.
* *Tenure Risk:* The first 6 months are the "danger zone" where attrition is highest.
* *Service Gap:* Fiber Optic users churn more frequently, likely due to price sensitivity or service quality issues.

## ⚙ How to Run
1.  Clone the repo:
    bash
    git clone [https://github.com/yourusername/churn-prediction.git](https://github.com/yourusername/churn-prediction.git)
    
2.  Install dependencies:
    bash
    pip install -r requirements.txt
    
3.  Open customer_churn_Prediction.ipynb to view the data cleaning and modeling steps.
4.  Open Churn_Dashboard.pbix to interact with the visual analytics.

---
Author: [Your Name]
Connect with me on [LinkedIn Profile Link]
