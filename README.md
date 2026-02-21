👩‍💼 IBM Employee Attrition Analysis & Prediction
🔍 Project Overview

Employee attrition is a major challenge for organizations due to increased hiring costs, productivity loss, and training expenses.

This project analyzes the IBM HR Analytics dataset to:

Identify key factors influencing employee attrition

Build a machine learning model to predict attrition

Develop an interactive Power BI dashboard for HR insights

The solution combines data analysis, predictive modeling, and business visualization.

🎯 Business Objective

High attrition negatively impacts organizational performance.

The objective of this project is to:

Understand why employees leave

Identify high-risk employee profiles

📊 Dataset Description

Total Records: 1470

Features: 35

Target Variable: Attrition (Yes/No)

Key characteristics:

~16% employees left

~84% employees stayed

Imbalanced classification problem

Features include:

Age

JobRole

MonthlyIncome

OverTime

JobSatisfaction

YearsAtCompany

WorkLifeBalance

Department

🧹 Data Preprocessing

The following steps were performed:

Removed irrelevant columns (EmployeeNumber, EmployeeCount, etc.)

Encoded categorical variables

Handled class imbalance

Train-test split

Feature scaling (if applied)

Special attention was given to class imbalance to ensure meaningful evaluation beyond accuracy.

📈 Exploratory Data Analysis (EDA)

Key Insights:

Employees working overtime show higher attrition rates

Lower monthly income correlates with higher attrition

Employees with fewer years at the company are more likely to leave

Job satisfaction and work-life balance significantly impact retention

These insights highlight critical drivers of employee turnover.

🤖 Machine Learning Model

A classification model was developed to predict employee attrition.

Evaluation Metrics Used:

Accuracy

Precision

Recall

F1-Score

After handling class imbalance, the model achieved improved recall, enabling better identification of employees at risk.

The focus was placed on recall and F1-score rather than accuracy due to the imbalanced nature of the dataset.

📊 Power BI Dashboard

An interactive HR dashboard was created to visualize attrition insights.

Dashboard Features:

Overall Attrition Rate

Attrition by Department

Overtime vs Attrition

Income vs Attrition

Job Role Analysis

Interactive filters for dynamic exploration

This dashboard enables HR teams to identify high-risk departments and employee segments effectively.

🚀 Business Recommendations

Based on analysis:

Improve work-life balance policies

Review compensation strategies for high-risk roles

Monitor employees with high overtime hours

Implement early retention programs for new employees

Predictive analytics allows HR to move from reactive to proactive retention strategy.

🛠 Tools & Technologies

Python

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn

Jupyter Notebook

Power BI

📌 Conclusion

This project demonstrates how machine learning and data visualization can be applied to solve real-world HR challenges.

By identifying key attrition drivers and building a predictive model, organizations can reduce turnover costs and improve employee retention strategies.
Enable HR to take proactive retention measures

The final outcome supports data-driven HR decision-making.
