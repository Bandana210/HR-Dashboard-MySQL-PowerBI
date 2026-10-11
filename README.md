# HR Analytics Dashboard | MySQL & Power BI

## Project Overview

This project analyzes employee data to explore workforce demographics, employment patterns, departmental trends, and employee distribution across locations. MySQL is used for data cleaning and SQL-based analysis, while Power BI is used to create dashboards that present key findings visually.

## Objectives

- Analyze employee demographics by gender, race, and age group.
- Compare employees working at headquarters and remotely.
- Examine employee distribution across states.
- Analyze hiring and termination trends over time.
- Compare gender distribution across departments and job titles.
- Identify departments with higher termination rates.
- Explore employee tenure across departments.

## Tools and Technologies

- **MySQL** — Data cleaning, transformation, and analysis.
- **Power BI** — Dashboard development and data visualization.
- **Jupyter Notebook** — Executing and documenting SQL queries.
- **CSV** — Source data format.

## Dataset

The project uses an HR dataset containing more than 22,000 employee records covering the period from 2000 to 2020.

The dataset contains employee information used to analyze demographics, employment dates, job roles, departments, work locations, and termination patterns.

## Data Cleaning and Preparation

The data preparation process includes:

- Renaming columns for consistency and readability.
- Converting date fields into appropriate date formats.
- Reviewing employee ages and excluding invalid age records from relevant analyses.
- Excluding future termination dates from analyses requiring completed employment periods.
- Preparing derived fields, including age groups, for demographic comparisons.

## SQL Analysis

SQL queries were developed to answer the following HR analytics questions:

1. What is the gender distribution of employees?
2. How are employees distributed across racial and ethnic groups?
3. What is the employee age distribution?
4. How many employees work at headquarters versus remotely?
5. What is the average employment duration of terminated employees?
6. How does gender distribution vary across departments and job titles?
7. How are employees distributed across job titles?
8. Which departments have the highest termination rates?
9. How are employees distributed across states?
10. How has employee count changed over time?
11. How does tenure vary across departments?

## Power BI Dashboard

The dashboard includes visualizations covering:

- Gender and race distribution.
- Employee age groups and demographic comparisons.
- Headquarters versus remote workforce distribution.
- State-wise employee distribution using a map.
- Changes in employee numbers over time.
- Gender distribution by department.
- Departmental termination-rate comparisons.
- Average employment duration.

## Key Findings

The initial analysis indicates that:

- Male employees outnumber female employees in the dataset.
- Employees aged 25–34 form the largest age group.
- Most employees work at headquarters rather than remotely.
- White employees represent the largest racial category in the dataset.
- Ohio has a comparatively large employee concentration.
- The employee-count trend increases over the analyzed period.
- Marketing and Training appear among the departments with the highest calculated termination rates.

These findings should be interpreted in the context of the dataset limitations and the calculation methods used.

## Limitations

- Records with invalid or negative ages were excluded from relevant analyses.
- Future termination dates were excluded where completed employment periods were required.
- Termination rates depend on the calculation method and the available employment records.
- Historical employee counts should be interpreted according to the date filters and counting logic used in the queries.

## Project Structure

```text
HR-Analytics-Dashboard/
├── Human Resources.csv
├── HR Data Cleaning.sql
├── HR Data Questions.sql
├── HR Final Queries.ipynb
├── HR Dashboard.pbix
├── HR Employee Report.pbix
├── HR Dashboard.pdf
└── README.md
```

## Skills Demonstrated

SQL querying, data cleaning, data validation, exploratory data analysis, date manipulation, demographic analysis, data visualization, and dashboard development.