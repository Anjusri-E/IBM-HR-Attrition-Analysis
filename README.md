# 🧑‍💼 IBM HR Analytics: Employee Attrition Analysis & Prediction  
A complete data cleaning, analysis, and machine learning project built using Python and Jupyter Notebook.  
This project explores key drivers of employee attrition and builds a predictive model to help HR teams improve retention strategies.

---

## 📊 **1. Project Overview**

Employee attrition is a major challenge for businesses.  
Using the IBM HR Analytics dataset, this project aims to:

- Understand **why employees leave the company**  
- Identify **high-risk employee groups**  
- Provide **actionable insights** to HR teams  
- Build an **ML model to predict attrition**  

---

## 🛠️ **2. Technologies Used**

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🧹 **3. Data Cleaning Steps**

✔ Removed duplicates  
✔ Fixed inconsistent strings  
✔ Encoded categorical variables  
✔ Handled missing values  
✔ Removed irrelevant columns  
✔ Normalized numerical features  
✔ Created cleaned dataset: `ibm_hr_cleaned.csv`

---

## 📈 **4. Exploratory Data Analysis (EDA)**

### 🔥 Key Insights:
- Employees working **overtime** are significantly more likely to leave  
- **Low monthly income** strongly correlates with attrition  
- Workers with **low job satisfaction** show higher attrition  
- Younger employees (25–35) tend to leave more  
- R&D department shows the **highest attrition**  
- Correlation heatmap highlights job satisfaction, overtime, income, and age as strong drivers

### 📊 Visualizations Generated:
- Attrition Distribution  
- Age Distribution  
- Monthly Income Distribution  
- Countplots for Gender & Department vs Attrition  
- Correlation Heatmap  
- Feature Importance (Random Forest)  

All visuals are saved in the **plots/** folder.

---

## 🤖 **5. Machine Learning Model**

Model Used: **Random Forest Classifier**

### 🔍 Performance:
- **Accuracy:** ~83%  
- **Precision for Attrition (1):** 0.43  
- **Recall for Attrition (1):** 0.31  

✔ The model can reliably flag potential high-risk employees  
✔ Feature importance reveals what HR should focus on

---

## 💡 **6. HR Insights & Recommendations**

### 🔥 High-Risk Employee Groups
- Employees working **overtime**  
- Employees with **low job satisfaction**  
- Employees with **low monthly income**  
- Younger employees (25–35 age group)  

### 🛠 Recommended Retention Strategies
- Reduce **mandatory overtime**  
- Increase **salary transparency**  
- Provide **career growth opportunities**  
- Conduct **regular job satisfaction surveys**  
- Improve **work–life balance policies**

---

## 📂 **7. Project Structure**


IBM_HR_ATTRITION_PROJECT/
├── ibm_hr_attrition.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── ibm_hr_cleaned.csv
├── requirements.txt
├── README.md
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