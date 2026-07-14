# 📊 Data Analytics Internship Project

## Overview

This repository contains the projects completed during my Data Analytics Internship. The objective of this internship was to apply data analytics techniques to real-world datasets using **Microsoft Excel** and **Microsoft SQL Server**.

The project demonstrates the complete data analysis workflow, including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- SQL Data Analysis
- Data Visualization in Microsoft Excel
- Business Insights and Reporting

---

## Project Objectives

- Clean and prepare raw datasets for analysis.
- Perform exploratory data analysis (EDA).
- Use SQL to answer business questions.
- Build interactive dashboards in Microsoft Excel.
- Generate actionable business insights.

---

## Tools Used

- Microsoft Excel
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)

---

# Project Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning (Excel)
      │
      ▼
Exploratory Data Analysis
      │
      ▼
SQL Analysis
      │
      ▼
Excel Dashboard
      │
      ▼
Business Insights
```

---

# 1. Data Cleaning and Preparation

## Description

The first stage of the project involved manually cleaning and preparing the raw dataset using Microsoft Excel.

The dataset contained several data quality issues that were corrected before analysis.

### Cleaning Tasks

- Removed duplicate records
- Handled missing values
- Corrected inconsistent formatting
- Standardized text entries
- Verified data consistency
- Prepared the dataset for analysis

---

## Raw Dataset

> Insert a screenshot of the original dataset here.

```md
![Raw Dataset]((https://github.com/allwell-dediribe/DecodeLabs-Internship/blob/main/Messy%20Data.png))
```

---

## Removing Duplicates

> Insert a screenshot showing duplicate removal.

```md
![Duplicate Removal](Images/Data-Cleaning/duplicate_removal.png)
```

---

## Cleaned Dataset

> Insert a screenshot of the cleaned dataset.

```md
![Cleaned Dataset](Images/Data-Cleaning/cleaned_dataset.png)
```

---

## Outcome

The dataset was successfully transformed into a clean and structured format suitable for analysis.

---

# 2. Exploratory Data Analysis (EDA)

## Description

Exploratory Data Analysis was performed in Microsoft Excel to understand the dataset and identify patterns, trends, and key performance indicators.

---

## Analysis Performed

- Descriptive Statistics
- Pivot Tables
- Frequency Distribution
- Quartile Analysis
- Trend Analysis
- Category Comparison

---

## Excel Features Used

- Pivot Tables
- Sorting
- Filtering
- Data Analysis ToolPak
- Excel Functions

---

## Descriptive Statistics

```md
![Descriptive Statistics](Images/EDA/descriptive_statistics.png)
```

---

## Pivot Tables

```md
![Pivot Tables](Images/EDA/pivot_tables.png)
```

---

## Quartile Analysis

```md
![Quartile Analysis](Images/EDA/quartile_analysis.png)
```

---

## Key Insights

- High-performing categories were identified.
- Summary statistics revealed variations across the dataset.
- Quartile analysis highlighted potential outliers.
- Pivot tables simplified trend analysis.

---

# 3. SQL Retail Data Analysis

## Description

Microsoft SQL Server was used to analyze an Online Retail Dataset by writing SQL queries to answer business questions and summarize business performance.

---

## Data Preparation

Before analysis, the following preprocessing tasks were completed:

- Imported the dataset into SQL Server
- Replaced blank Coupon Code values with **"No Coupon"**
- Created **Order Year** and **Order Month** columns
- Verified data types

---

## SQL Concepts Used

- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- UPDATE
- Aggregate Functions
- Date Functions

---

## Example Query — Filtering Records

```sql
SELECT *
FROM OnlineRetail
WHERE Payment_Method = 'Credit Card';
```

```md
![Filtering Records](Images/SQL/filtering_records.png)
```

---

## Example Query — GROUP BY

```sql
SELECT Payment_Method,
       SUM(Total_Revenue) AS Revenue
FROM OnlineRetail
GROUP BY Payment_Method;
```

```md
![GROUP BY](Images/SQL/groupby.png)
```

---

## Example Query — HAVING

```sql
SELECT Product,
       SUM(Total_Revenue) AS Revenue
FROM OnlineRetail
GROUP BY Product
HAVING SUM(Total_Revenue) > 2000;
```

```md
![HAVING Clause](Images/SQL/having_clause.png)
```

---

## Business Insights

| Metric | Value |
|---------|-------:|
| Total Orders | 1,200 |
| Total Revenue | $1,264,761.96 |
| Average Order Value | $1,053.97 |
| Average Quantity Ordered | 2 |
| Cancelled Orders | 251 |

### Product Insights

- Chair generated the highest revenue.
- Printer ranked second.
- Laptop ranked third.

### Customer Insights

- Online Payments recorded the highest number of transactions.
- Credit Card generated the highest revenue.
- Instagram was the highest-performing referral source.

---

# 4. Data Visualization (Microsoft Excel)

## Description

Interactive dashboards were created in Microsoft Excel to present key business insights and support decision-making.

---

## Dashboard Features

- KPI Summary
- Revenue Analysis
- Sales Trend
- Product Performance
- Payment Method Analysis
- Referral Source Analysis

---

## Dashboard Overview

```md
![Dashboard Overview](Images/Dashboard/dashboard_overview.png)
```

---

## KPI Dashboard

```md
![KPI Dashboard](Images/Dashboard/kpi_dashboard.png)
```

---

## Sales Trend

```md
![Sales Trend](Images/Dashboard/sales_trend.png)
```

---

## Product Performance

```md
![Product Performance](Images/Dashboard/product_performance.png)
```

---

## Payment Method Analysis

```md
![Payment Analysis](Images/Dashboard/payment_analysis.png)
```

---

# Challenges Encountered

- Cleaning inconsistent data manually.
- Removing duplicate records.
- Handling missing values.
- Organizing large datasets.
- Preparing data before SQL analysis.

---

# Recommendations

- Increase marketing efforts for high-performing products.
- Improve sales strategies for underperforming products.
- Investigate cancelled orders.
- Continue optimizing online payment methods.
- Leverage successful referral channels such as Instagram.

---

# Repository Structure

```text
Data-Analytics-Internship-Project
│
├── Data
│   ├── Raw Dataset.xlsx
│   └── Cleaned Dataset.xlsx
│
├── Excel
│   ├── Data Cleaning.xlsx
│   ├── Exploratory Data Analysis.xlsx
│   └── Dashboard.xlsx
│
├── SQL
│   ├── SQL Queries.sql
│   └── SQL Analysis Report.pdf
│
├── Images
│   ├── Data-Cleaning
│   ├── EDA
│   ├── SQL
│   └── Dashboard
│
├── Reports
│   └── Final Internship Report.pdf
│
└── README.md
```

---

# Skills Demonstrated

- Data Cleaning
- Data Preparation
- Exploratory Data Analysis (EDA)
- Microsoft Excel
- SQL
- Pivot Tables
- Data Analysis
- Business Reporting
- Analytical Thinking
- Problem Solving

---

# Conclusion

This internship project demonstrates the complete data analysis process—from cleaning raw data and performing exploratory analysis to querying data with SQL and presenting insights through Microsoft Excel dashboards. The project strengthened practical skills in data preparation, analysis, visualization, and business reporting while reinforcing the importance of data-driven decision-making.
