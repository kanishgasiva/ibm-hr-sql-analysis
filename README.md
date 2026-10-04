# HR Employee Attrition Analysis Using SQL

Project Overview
--
Analyzed employee attrition data using SQL to identify patterns and factors associated with employee turnover

Objective
--
To understand overall attrition and identify employee groups with higher attrition rates based on department, job role, age, tenure, overtime, job satisfaction, and work-life balance

Dataset
--
Source: Kaggle

Link: [ kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset ](https://kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

Contains employee-level HR information for 1,470 employees, including demographics, job details, satisfaction measures, work-life factors, and attrition status

Project Workflow
--
- Load and explore the HR dataset in SQL.
-  Calculate overall and category-wise attrition rates.
- Analyze key factors affecting employee attrition.
- Identify high-attrition employee profiles.
- Summarize key HR insights.

Analysis & Questions
--
1. What is the overall employee attrition rate?
2. Which departments have the highest attrition rates?
3. Which job roles have the highest attrition rates?
4. Which age groups have the highest attrition rates?
5. How does tenure at the company relate to attrition?
6. Does overtime contribute to higher attrition?
7. How does job satisfaction relate to attrition?
8. How does work-life balance impact attrition?
9. What is the profile of employees with higher attrition rates?

## Key Insights

* Overall employee attrition rate was **16.12%**, with 237 employees leaving out of 1,470.
* Employees with shorter tenure showed higher attrition rates.
* Employees working overtime had higher attrition rates.
* Lower job satisfaction was associated with higher attrition.
* Lower work-life balance was associated with higher attrition.
* Combined employee and job characteristics were used to identify higher-risk employee groups.

Files
--
* `ibm_hr_analysis.sql` — Data cleaning and exploratory analysis queries
* `hr_attrition_raw.csv` — Dataset
