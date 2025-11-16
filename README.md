📊 IBM HR Analytics — Employee Attrition & Performance
🔍 Data Cleaning • Exploratory Data Analysis (EDA) • Machine Learning
Tools: Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-Learn, Jupyter Notebook
📁 Project Overview

This project analyzes the IBM HR Employee Attrition dataset to identify the factors contributing to employee turnover.
The workflow includes:

Data cleaning

Exploratory data analysis

Visualizations

Machine learning model to predict attrition

Insights & HR recommendations

🚀 Objectives

✔ Understand why employees leave
✔ Find patterns behind attrition
✔ Identify high-risk employee groups
✔ Provide actionable HR retention insights

🧹 1. Data Cleaning Steps

Removed duplicates

Standardized categorical values

Handled missing values

Created new features

Encoded categorical variables for ML

📊 2. Exploratory Data Analysis

Key visualizations include:

Attrition by age

Attrition by department

Attrition by job role

Monthly income vs attrition

Work-life balance analysis

Correlation heatmap

All plots are stored in the plots/ folder.

🤖 3. Machine Learning Model

A Random Forest Classifier was trained.

📌 Accuracy: ~83%
📌 Key Predictors:

Overtime

Monthly Income

Job Role

Age

Job Satisfaction

Environment Satisfaction

The model shows that overworked, underpaid, and dissatisfied employees are most likely to leave.

📝 4. HR Insights & Recommendations
🔥 High-Risk Groups

Employees working overtime

Employees with low job satisfaction

Low monthly income employees

Younger employees (25–35 age group)

🛠 Recommended Retention Strategies

Reduce mandatory overtime

Increase salary transparency

Provide growth opportunities

Conduct job satisfaction surveys

Improve work–life balance policies

IBM_HR_ATTRITION_PROJECT/
│
├── ibm_hr_attrition.ipynb                  # Main notebook
├── WA_Fn-UseC_-HR-Employee-Attrition.csv   # Raw dataset
├── ibm_hr_cleaned.csv                      # Cleaned dataset
├── requirements.txt
│
└── plots/
    ├── attrition_distribution.png
    ├── Age_distribution.png
    ├── MonthlyIncome_distribution.png
    ├── Department_countplot.png
    ├── Gender_countplot.png
    ├── correlation_heatmap.png
    └── feature_importance.png


📎 Dataset Source

IBM HR Analytics Employee Attrition Dataset

🔗 GitHub Repository

👉 https://github.com/Anjusri-E/IBM-HR-Attrition-Analysis