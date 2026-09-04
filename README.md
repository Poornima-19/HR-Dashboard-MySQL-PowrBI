# 📊 HR Analytics Dashboard — MySQL + Power BI

> **End-to-end HR analytics portfolio project** turning 22,000+ employee records into workforce insights and an interactive Power BI report.

## 🎯 Business Problem

HR teams need a clear view of workforce composition, turnover, tenure, locations, and employee trends. This project uses SQL to prepare and analyze HR data, then Power BI to communicate the findings visually.

## 🔄 End-to-End Workflow

`Raw HR Data → Data Quality Checks → SQL Cleaning → Business Questions → Analysis → Power BI Dashboard → Insights`

## 🛠️ Tools

| Tool | Role |
|---|---|
| **MySQL / SQL** | Data cleaning, transformation, filtering and analysis |
| **Power BI** | KPI design, interactive visualization and reporting |

## 📊 Dataset

The dataset contains **22,000+ employee records covering 2000–2020**, with attributes including demographics, employment dates, departments, job titles, locations and termination information.

## 🧹 Data Preparation

- Created and loaded the HR database
- Standardized employee and date fields
- Converted dates into analysis-ready formats
- Derived employee age
- Identified invalid records
- Handled negative-age records
- Handled future termination dates
- Prepared clean data for workforce analysis

## 🔎 Business Questions

- How is the workforce distributed by gender, race/ethnicity and age?
- How are employees distributed across departments and job titles?
- How many employees work at headquarters versus remotely?
- Which departments have the highest turnover?
- What is the average employment length of terminated employees?
- How are employees distributed geographically?
- How has employee count changed over time?
- What is the average tenure by department?

## 💡 Key Insights

- Employees aged **25–34** form the largest age group, followed by **35–44**.
- Headquarters employees outnumber remote employees.
- Terminated employees have an average employment length of approximately **7 years**.
- Overall gender distribution is male-dominant, while several departments show a relatively balanced mix.
- **Marketing** has the highest turnover rate, followed by **Training**.
- **Ohio** has a large concentration of employees in the dataset.
- Employee count shows a positive net change across the analyzed period.
- Average departmental tenure is approximately **8 years**, with variation between departments.

## 📈 Dashboard

The Power BI report covers:

**Workforce Demographics · Age & Gender · Departments · Job Titles · Geography · Turnover · Tenure · Workforce Trends**

### Dashboard files

- `HR Dashboard.pbix` — interactive Power BI report
- `HR Dashboard.pdf` — PDF export

> 💡 **Portfolio improvement:** add a dashboard screenshot under `images/` and embed it here to give recruiters an immediate visual preview.

## ⚠️ Data Quality & Limitations

- **967 records** with negative ages were excluded.
- **1,599 records** with future termination dates were excluded from relevant termination analysis.
- Workforce analysis focuses on employees aged **18 and above**.
- Termination calculations use valid termination dates within the analysis period.

## 🧠 Skills Demonstrated

`SQL` `MySQL` `Data Cleaning` `Data Validation` `EDA` `Aggregation` `HR Analytics` `Power BI` `Data Visualization` `Business Insights`

## 📁 Project Structure

```text
HR-Dashboard-MySQL-PowrBI/
├── HR Data Cleaning.sql
├── HR Data Questions.sql
├── HR Dashboard.pbix
├── HR Dashboard.pdf
└── README.md
```

## 🚀 Why This Project Matters

This project demonstrates a complete analytics workflow: **define business questions → validate and clean data → analyze with SQL → identify patterns → communicate findings through a dashboard**.

⭐ Explore the SQL scripts and Power BI report to see the complete workflow.
