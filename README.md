# HR Analytics Dashboard — MySQL & Power BI

An end-to-end **HR analytics project** using **MySQL for data cleaning and analysis** and **Power BI for data visualization**.

The goal is to transform raw employee data into meaningful insights around **workforce demographics, employee distribution, turnover, tenure, and workforce trends**.

---

## 📌 Project Overview

This project uses an HR dataset containing **22,000+ records covering 2000–2020**. MySQL was used for data preparation and analysis, followed by Power BI visualization. fileciteturn14file0L2-L2

**Workflow:**

`Raw Data → Data Cleaning → SQL Analysis → Insights → Power BI Dashboard`

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **MySQL / MySQL Workbench** | Data cleaning, transformation and analysis |
| **SQL** | Business questions, aggregations and workforce analysis |
| **Power BI** | Data visualization and dashboarding |

---

## 🧹 Data Preparation

The SQL workflow includes:

- Creating the HR database and employee table
- Loading the HR dataset
- Standardizing employee and date fields
- Converting birth, hire and termination dates into usable formats
- Creating an employee age field
- Identifying invalid and unusual records
- Filtering records for analysis based on age and valid termination dates

The cleaning script includes checks for invalid ages and future termination dates. fileciteturn6file0L2-L2

---

## 🔎 Business Questions

The analysis answers questions around:

1. Gender distribution
2. Race/ethnicity distribution
3. Employee age distribution
4. Headquarters vs. remote employees
5. Average employment length of terminated employees
6. Gender distribution across departments and job titles
7. Job-title distribution
8. Department-level turnover rate
9. Employee distribution by location/state
10. Employee-count changes over time
11. Average tenure by department

These questions are implemented through SQL queries in the project. fileciteturn7file0L2-L2

---

## 📊 Key Insights

- Employees aged **25–34** form the largest age group, followed by **35–44**.
- More employees work at headquarters than remotely.
- Average employment length for terminated employees is approximately **7 years**.
- Gender distribution across departments is relatively balanced, with a higher overall number of male employees.
- **Marketing** has the highest turnover rate, followed by **Training**.
- **Ohio** has a large concentration of employees.
- Employee count shows a positive net change over the analyzed period.
- Average departmental tenure is approximately **8 years**, with differences between departments. fileciteturn12file0L2-L2

---

## 📈 Power BI Dashboard

The analysis was visualized in **Power BI** to make workforce patterns easier to explore and communicate.

The dashboard covers areas including:

- Workforce demographics
- Age and gender distribution
- Department and job-title analysis
- Location distribution
- Employee turnover
- Employee tenure
- Workforce trends over time

**Dashboard files:**

- `HR Dashboard.pbix` — Power BI dashboard
- `HR Dashboard.pdf` — Dashboard export

---

## 📁 Project Structure

```text
HR-Dashboard-MySQL-PowrBI/
│
├── HR Data Cleaning.sql
├── HR Data Questions.sql
├── HR Dashboard.pbix
├── HR Dashboard.pdf
└── README.md
```

---

## ⚠️ Data Quality & Limitations

Data quality checks identified records that required special handling:

- **967 records** with negative ages were excluded.
- **1,599 records** with future termination dates were excluded from relevant analysis.
- Main workforce queries use employees aged **18 and above**.
- Termination-based calculations use termination dates on or before the analysis date. fileciteturn12file0L2-L2

Documenting these limitations is important because analytical results depend on the quality and assumptions applied to the source data.

---

## 💡 Skills Demonstrated

- SQL data cleaning
- Data transformation
- Data validation
- Exploratory data analysis
- Aggregation and grouping
- HR / workforce analytics
- Business-question development
- Data visualization
- Power BI dashboard development
- Translating analysis into business insights

---

## 🎯 Key Learning

This project helped me practice an end-to-end analytics workflow: **understanding business questions, preparing data, analyzing patterns, visualizing results, and communicating insights**.

It also reinforced the importance of validating data and documenting analytical limitations before drawing conclusions.

---

⭐ **Thanks for visiting this project. Feel free to explore the SQL scripts and dashboard files.**
