# 💼 HR Analytics with Power BI – AdventureWorks 2022

This project explores *Human Resources data* using *Power BI* dashboards, providing key insights into employee demographics, work schedules, department trends, compensation, and attrition.

## 📌 Project Overview

- *Title*: Human Resources Analytics: Workforce Insights through Data  
- *Data Source*: Microsoft AdventureWorks 2022 (SQL Server)  
- *Tool Used*: Power BI  
- *Focus*: HR Metrics, Workforce Demographics, Shift Patterns, Attrition, Compensation  

## 🧩 Data Modeling

10 interconnected tables from the *AdventureWorks 2022* database were imported and modeled:

- HumanResources.Employee, Department, Shift
- Person.Address, StateProvince, CountryRegion
- EmployeePayHistory, etc.

Steps included:

- Cleaning & formatting data  
- Creating hierarchies (e.g., Country > State > City)  
- Building calculated columns and DAX measures  

## 📊 Dashboards

### 1. Employee Overview

- Total Employees: 290  
- Avg Age: 46.54  
- Visuals: Department breakdown, gender distribution, marital status, geographic map  

### 2. Work Shifts Overview

- Shift distribution: Day, Evening, Night  
- Hiring trends by year  
- Department vs Shift visualization  
- Gender distribution by shift  

### 3. Department Insights

- Avg Salary: $3.07K  
- Attrition Rate: 1.72%  
- Salary vs Attrition correlation  
- Department sizes and compensation comparison  

### 4. Workforce Trends

- Avg Tenure: 5.86 years  
- Tenure distribution  
- Attrition over time (peak in 2008)  
- Word cloud for job roles  

## 🎯 Key Insights

- Workforce is aging and experienced – mostly aged 35–54  
- Highest attrition in Engineering and QA departments  
- Day shift is dominant; evening shift has gender balance  
- Most employees have 5–9 years tenure  

## 📁 Preview or Download the Dashboard

You can view the full Power BI report:

> 🔗 [View Power BI Report (.pbix)](https://github.com/Thalyta99/HR-Business-Analysis/blob/main/HR-Business-Analysis.pbit)  
> To view this file, download and open it using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).

## 🛠 Technologies Used

- Power BI  
- SQL Server  
- DAX  
- AdventureWorks 2022 Dataset
