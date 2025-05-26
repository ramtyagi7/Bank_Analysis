# Bank Data Analysis  
*Using Power BI, Python, MS SQL Server, and Excel*

---

## 📂 Project Overview

This project focuses on analyzing bank customer data to extract meaningful insights about their financial behaviors. The dataset originates from an Excel file, which is imported into **MS SQL Server** for storage and initial transformation. Further exploratory data analysis (EDA) and visualization are performed using **Python** libraries — Pandas, NumPy, and Seaborn. Finally, interactive dashboards are built in **Power BI** to present key findings in an accessible format.

---

## 🎯 Project Purpose

- Import bank dataset (Excel) into MS SQL Server  
- Transform and clean data using Python (Pandas, NumPy)  
- Perform comprehensive EDA:  
  - Univariate analysis  
  - Bivariate analysis  
  - Heatmaps  
  - Numerical & descriptive statistics  
  - Correlation matrix using regression  
- Generate useful business insights  
- Create an interactive Power BI dashboard for visualization

---

## 🔎 Exploratory Data Analysis (EDA)

We analyzed the dataset using various techniques:

- **Univariate Analysis:** Examining individual variables to understand distribution and key statistics  
- **Bivariate Analysis:** Investigating relationships between pairs of variables  
- **Heatmaps:** Visualizing correlations between features  
- **Numerical & Descriptive Analysis:** Summarizing data using statistical measures  
- **Correlation Matrix with Regression:** Understanding linear dependencies among variables

---

## 💡 Key Insights

### Deposits and Savings Behavior  
- Strong correlation between **Bank Deposits** and **Savings Accounts** suggests overlapping financial activity — customers who deposit funds often maintain or grow their savings balances.

### Income, Age, and Accumulation  
- Moderate correlations between **Age**, **Estimated Income**, and balances in Superannuation, Savings, and Checking accounts indicate typical financial lifecycle trends: older and higher-income individuals accumulate more savings and retirement funds.

### Low Correlation with Properties Owned  
- Property ownership shows weak correlation with banking variables, possibly due to external influences like location or market conditions that are not reflected in the dataset.

### Business vs. Personal Banking  
- Moderate link between **Business Lending** and **Bank Loans** indicates some customers carry both personal and business debt. Business lending correlates weakly with deposits and property metrics, implying it serves distinct customer segments.

---

## 📊 Power BI Dashboard Overview

The dashboard contains **3 main pages**, each designed to explore different aspects of the banking data:

| Page            | Description                                                                                         |
|-----------------|-------------------------------------------------------------------------------------------------|
| **Loan Analysis**    | Filters: Banking Relationship, Gender, Investment Advisor (Top 5 Years) <br> Visuals: 4 KPIs, Donut chart (Bank Loans by Income Band), Clustered column charts (Nationality, Banking Relationship), Clustered bar chart (Occupation) |
| **Deposit Analysis** | Same filters as Loan Analysis <br> Visuals: 4 KPIs, Donut chart (Bank Deposits by Income Band), Clustered column charts, Clustered bar chart |
| **Summary**          | Multiple KPIs summarizing total loans, total deposits, total clients, and more                  |

---

## 🛠 Technologies Used

- **MS SQL Server:** Data storage, import, and transformation  
- **Python:** Data manipulation and analysis (Pandas, NumPy, Seaborn)  
- **Power BI:** Dashboard creation and data visualization  
- **Excel:** Original dataset source and supplemental data handling

---

## 📋 How to Use This Project

1. Import the Excel dataset into **MS SQL Server**.  
2. Use Python scripts to transform data and perform EDA.  
3. Load transformed data into **Power BI** to build and interact with dashboards.

---
*Thank you for exploring this project!*




