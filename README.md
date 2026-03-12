# Medicare Inpatient Hospital Cost and Provider Performance Analysis
## 🎯 Business Problem
Healthcare costs vary significantly across hospitals, states, and medical procedures. 
Medicare, as a major healthcare payer in the United States, spends billions of dollars annually on inpatient hospital services. 
Understanding which hospitals, procedures (DRGs), and regions generate the highest costs is essential for improving transparency and controlling healthcare spending.
The goal of this project is to analyze Medicare inpatient hospital data to identify cost patterns, provider performance, and patient payment burdens across different hospitals and states
## 📊 Project Overview
This project analyzes the **Medicare Inpatient Hospitals by Provider and Service dataset (2023)** to understand hospital charges, Medicare reimbursements, and patient financial responsibility.

The analysis focuses on identifying:

- Most expensive DRG procedures

- Providers with the highest charges and payments

- State-level healthcare spending

- Differences between submitted charges and Medicare payments

An interactive dashboard was created to visualize these insights.
### 📂 Dataset
The <a href='https://data.cms.gov/provider-summary-by-type-of-service/medicare-inpatient-hospitals/medicare-inpatient-hospitals-by-provider-and-service'>dataset</a> used in this project was obtained from the Centers for Medicare & Medicaid Services (CMS).  
It provides detailed information about inpatient hospital services, including providers, DRG procedures, discharge counts, and Medicare payment amounts.
### 🛠 Tools Used
- **EXCEL** – Data Cleaning and Exploratory Data Analysis (EDA)
- **Power BI** – Data Modeling, DAX Calculations, and Dashboard Visualization
### Process
**Data Cleaning**

Data cleaning was performed in Excel before analysis. Steps included:

- Removing duplicate records

- Checking for missing values

- Formatting numeric columns

- Standardizing column names

- Creating calculated metrics such as
1. **Avg Patient Paid** = Avg Total Payment Amount − Avg Medicare Payment Amount
2. **Ratio Of payment By Medicare** = Avg Medicare Payment Amount/Avg Total Payment Amount
3. **Ratio Of payment By Patient**=  Avg Patient Paid/Avg Total Payment Amount
