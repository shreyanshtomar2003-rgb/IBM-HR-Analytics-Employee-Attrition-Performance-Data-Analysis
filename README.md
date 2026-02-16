# IBM-HR-Analytics-Employee-Attrition-Performance-Data-Analysis
IBM HR Employee Attrition Analysis
📌 Project Overview

Employee attrition is a critical challenge for organizations, directly impacting productivity, hiring costs, and workforce stability.
This project analyzes a fictional HR dataset created by IBM data scientists to uncover the key factors that lead to employee attrition and provide data-driven insights for HR decision-making.

The project demonstrates an end-to-end data analytics workflow using Python and Power BI, with all analysis performed inside a Jupyter Notebook.

🎯 Business Objectives

The main goals of this project are:

Understand the overall employee attrition rate

Identify job roles and employee segments with high attrition

Analyze how factors such as income, education, overtime, work-life balance, and distance from home impact attrition

Build an interactive dashboard to support HR decision-making

🗂 Dataset Information

Dataset Name: IBM HR Employee Attrition

Source: Fictional dataset by IBM Data Scientists

Rows: 1,470 employees

Columns: 35 features

Target Variable: Attrition (Yes / No)

Key Feature Categories:

Demographics: Age, Gender, Marital Status

Job Details: JobRole, JobLevel, Department

Compensation: MonthlyIncome, DailyRate, HourlyRate

Satisfaction Metrics: JobSatisfaction, WorkLifeBalance, EnvironmentSatisfaction

Behavioral Factors: OverTime, DistanceFromHome, YearsAtCompany

🛠 Tools & Technologies Used

Python: Pandas, NumPy, Matplotlib, Seaborn

Jupyter Notebook: Data Cleaning, EDA & Business Analysis

Power BI: Interactive dashboards & KPIs

MS Word / PDF: Final project reporting

🔄 Project Workflow
1️⃣ Data Cleaning & Exploratory Data Analysis (Jupyter Notebook)

All data processing and analysis were performed inside the Jupyter Notebook:

📓 IBM HR Employee Attrition.ipynb

Key steps included:

Loading the dataset using Pandas

Checking for missing values and duplicate records

Mapping encoded categorical variables into meaningful labels

Performing exploratory data analysis using:

Correlation heatmaps

Boxplots (Monthly Income vs Attrition)

Bar charts (Attrition by Job Role)

Grouped analysis by education, job role, and attrition

Identifying early patterns and trends related to employee exits

2️⃣ Business Analysis Using Python (Jupyter Notebook)

Instead of SQL, all business questions were answered using Pandas groupby and aggregation logic inside the notebook:

Examples of analysis:

Overall attrition rate calculation

Attrition breakdown by job role

Distance from home by job role and attrition

Average monthly income by education and attrition

Overtime and work-life balance impact on attrition

Gender and marital status attrition analysis

This approach keeps the entire analytical logic transparent, reproducible, and notebook-driven.

3️⃣ Dashboard Creation (Power BI)

An interactive HR Attrition Dashboard was built using Power BI to visualize insights from the notebook:

Dashboard features include:

KPI Cards:

Total Employees

Attrition Rate

Average Monthly Income

Average Years at Company

Attrition by Job Role

Monthly Income by Education & Attrition

Distance From Home vs Attrition

Work-Life Balance & Overtime impact

Interactive slicers (Department, Gender, Job Role, Education)

📈 Key Insights

Employees with lower monthly income show significantly higher attrition

Overtime is one of the strongest drivers of employee exits

Poor work-life balance strongly correlates with attrition

Certain job roles (Sales & Research-related roles) experience higher turnover

Employees with longer commute distances are more likely to leave

✅ Recommendations

Improve compensation structure for lower-income roles

Reduce overtime dependency through better workforce planning

Strengthen work-life balance policies

Implement targeted retention programs for high-attrition job roles

Focus on employee satisfaction and career development initiatives

📊 Project Outputs

✔ Jupyter Notebook with full analysis (.ipynb)

✔ Python-based business analysis & visualizations

✔ Power BI interactive dashboard

✔ Detailed project report (Word & PDF)

✔ Visual documentation for portfolio use

🚀 Conclusion

This project demonstrates how Python-based analytics and visualization tools can effectively support HR decision-making.
By combining Jupyter Notebook analysis with Power BI dashboards, the project provides a complete, real-world HR analytics solution.
