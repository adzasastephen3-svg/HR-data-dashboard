## Project Overview

This repository contains a Power BI report and four supporting CSV files. The report is organized into three pages:

1. **Home** – the dashboard landing page and navigation.
2. **Employee Info** – employee-level information, including employee names and lists of employees flagged for promotion or retrenchment.
3. **Details** – workforce summary cards and visual breakdowns, including gender, job satisfaction, performance rating, department, promotion, and retrenchment information.

The Power BI report includes KPI cards, charts, tables, page-navigation buttons, and a green-themed visual design.

## Files in This Project

| File | Description |
|---|---|
| `Hr_data_analytics.pbix` | Power BI dashboard/report. |
| `hr_analytics_synthetic_dataset.csv` | Main employee dataset containing 2,000 records and 35 fields. |
| `hr_employee_names_2000.csv` | Employee-number-to-name lookup containing 2,000 records. |
| `data_promotion.csv` | Employee promotion flag list containing 64 records. |
| `data_retrenched.csv` | Employee retrenchment flag list containing 2,000 records. |

## Dataset Fields

The main dataset includes employee and job-related attributes such as:

- **Demographics:** Age, Gender, MaritalStatus, Education, EducationField.
- **Employment:** Department, JobRole, JobLevel, BusinessTravel, YearsAtCompany, TotalWorkingYears.
- **Compensation:** DailyRate, HourlyRate, MonthlyIncome, MonthlyRate, PercentSalaryHike.
- **Employee experience:** Attrition, EnvironmentSatisfaction, JobInvolvement, JobSatisfaction, RelationshipSatisfaction, WorkLifeBalance, OverTime.
- **Career development:** NumCompaniesWorked, TrainingTimesLastYear, YearsInCurrentRole, YearsSinceLastPromotion, YearsWithCurrManager.
- **Performance and benefits:** PerformanceRating, StockOptionLevel.

The main dataset has 35 columns and 2,000 employee records.

## Dashboard Features

Based on the supplied Power BI report:

- Workforce KPI cards, including total employees and gender-related figures.
- Gender representation and percentage breakdowns.
- Job satisfaction distribution, with categories such as High, Median, Low, and Very Low.
- Performance rating distribution, including Medium and High Rating categories.
- Department-level comparison of promotion and retrenchment indicators.
- A job-role summary table with total employee, promotion, and retrenchment information.
- Employee information tables and navigation between report pages.

## Data Snapshot

The following figures were calculated directly from the supplied CSV files:

| Metric | Observed value |
|---|---:|
| Employees in main dataset | 2,000 |
| Female employees | 966 |
| Male employees | 1,034 |
| Employees marked with Attrition = Yes | 321 |
| Employees marked with Attrition = No | 1,679 |
| Average employee age | 36.92 years |
| Average monthly income | 8,537.08 |
| Employees with OverTime = Yes | 578 |
| Employees with OverTime = No | 1,422 |
| Promotion-flag records | 64 |
| Retrenchment-flag records | 232 |

Department distribution in the main dataset

| Department | Employees |
|---|---:|
| Research & Development | 1,367 |
| Sales | 388 |
| Human Resources | 245 |


## Tools and Technologies

- **Microsoft Power BI** – report design, data visualization, and dashboard navigation.
- **CSV** – source data files.

## How to Use

1. Download or clone this repository.
2. Open `Hr_data_analytics.pbix` using Microsoft Power BI Desktop.
3. If Power BI prompts for data-source locations, point it to the CSV files included in the repository and update the queries as required.
4. Explore the **Home**, **Employee Info**, and **Details** pages using the report navigation buttons.

## Project Purpose

This project demonstrates how employee data can be organized and presented in an interactive HR dashboard. It brings workforce demographics, employee experience, performance, and workforce-status indicators into one Power BI report to support exploration and reporting.

