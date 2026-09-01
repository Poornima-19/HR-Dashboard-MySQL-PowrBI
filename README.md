# HR Analytics Dashboard — MySQL & Power BI

> **End-to-end HR analytics project** focused on workforce demographics, turnover, tenure, and employee trends.

This project demonstrates how raw HR data can be transformed into business-ready insights using **SQL for data preparation and analysis** and **Power BI for visualization**.

## 🎯 Business Objective

Analyze workforce patterns and answer practical HR questions around:

- Workforce demographics
- Age and gender distribution
- Department and job-title composition
- Employee location
- Turnover
- Employee tenure
- Workforce changes over time

## 🔄 Analytics Workflow

`Raw HR Data → Data Cleaning → SQL Analysis → Business Insights → Power BI Dashboard`

## 🛠️ Tools & Technologies

| Technology | Application |
|---|---|
| **MySQL / MySQL Workbench** | Data cleaning and analysis |
| **SQL** | Business questions, filtering, aggregation and workforce metrics |
| **Power BI** | Interactive data visualization and dashboarding |

## 📊 Dataset

The project uses an HR dataset containing **22,000+ employee records covering 2000–2020**.

The analysis includes employee attributes related to demographics, employment dates, departments, job titles, locations and termination information.

## 🧹 Data Preparation

The SQL cleaning process includes:

- Creating the database and employee table
- Loading the source HR dataset
- Standardizing employee and date fields
- Converting date fields into usable formats
- Deriving employee age
- Identifying invalid records
- Handling negative-age records
- Handling future termination dates
- Preparing clean data for workforce analysis

## 🔎 Key Business Questions

The analysis investigates:

1. What is the gender distribution of employees?
2. What is the race/ethnicity distribution?
3. How are employees distributed across age groups?
4. How many employees work at headquarters versus remotely?
5. What is the average employment length of terminated employees?
6. How does gender vary across departments and job titles?
7. Which job titles have the highest employee counts?
8. Which departments have the highest turnover?
9. How are employees distributed across locations/states?
10. How has employee count changed over time?
11. What is the average tenure by department?

## 💡 Key Insights

- Employees aged **25–34** form the largest age group, followed by **35–44**.
- Headquarters employees outnumber remote employees.
- Terminated employees have an average employment length of approximately **7 years**.
- Overall employee gender distribution is male-dominant, while several departments show a relatively balanced mix.
- **Marketing** has the highest turnover rate, followed by **Training**.
- **Ohio** has a large concentration of employees in the dataset.
- Employee count shows a positive net change across the analyzed period.
- Average departmental tenure is approximately **8 years**, with variation between departments.

## 📈 Power BI Dashboard

The Power BI component converts the SQL analysis into an easy-to-explore visual report covering:

- Workforce demographics
- Age and gender analysis
- Department and job-title distribution
- Geographic distribution
- Turnover analysis
- Tenure analysis
- Workforce trends over time

**Dashboard assets:**

- `HR Dashboard.pbix` — Power BI report
- `HR Dashboard.pdf` — PDF export

## ⚠️ Data Quality & Limitations

The analysis documents important data-quality decisions:

- **967 records** with negative ages were excluded.
- **1,599 records** with future termination dates were excluded from relevant termination analysis.
- Workforce analysis focuses on employees aged **18 and above**.
- Termination-based calculations use valid termination dates within the analysis period.

These assumptions should be considered when interpreting the results.

## 🧠 Skills Demonstrated

- SQL data cleaning
- Data validation
- Data transformation
- Exploratory data analysis
- Aggregation and grouping
- HR / workforce analytics
- Business-question development
- Power BI dashboard development
- Data visualization
- Insight communication

## 📁 Project Structure

```text
HR-Dashboard-MySQL-PowrBI/
├── HR Data Cleaning.sql
├── HR Data Questions.sql
├── HR Dashboard.pbix
├── HR Dashboard.pdf
└── README.md
```

## 🚀 What This Project Demonstrates

This project represents a complete analytics workflow rather than only a dashboard: **define business questions → clean and validate data → analyze with SQL → identify patterns → communicate findings visually**.

---

⭐ If you find this project useful, feel free to explore the SQL scripts and Power BI report.