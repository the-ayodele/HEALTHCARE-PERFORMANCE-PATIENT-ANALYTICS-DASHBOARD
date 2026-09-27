# Healthcare Performance & Patient Analytics Dashboard

## Overview

An interactive Power BI dashboard for monitoring healthcare financial performance, patient activity, and operational trends. It converts healthcare data into KPIs and actionable insights for data-driven decision-making.

## Business Problem

Healthcare organizations need a clear view of financial and patient performance across states, departments, services, and time periods.

This project helps answer questions such as:

- What are the revenue, cost, profit, and margin levels?
- How is revenue performing against target?
- Which states, departments, and services drive performance?
- What are the monthly revenue trends?
- What is the patient distribution by age group?
- What proportion of patients are new or returning?

## Project Objectives

- Monitor key healthcare financial KPIs.
- Analyze patient demographics and visit patterns.
- Compare performance across states, departments, and services.
- Track monthly revenue and target achievement.
- Generate dynamic executive insights using DAX.
- Provide an interactive management reporting solution.

## Tools & Technologies

- **Power BI** — Dashboard development, data modeling, and visualization.
- **DAX** — Measures, KPIs, calculations, and dynamic executive insights.
- **Power Query (M)** — Data cleaning and transformation.
- **Microsoft Excel** — Source dataset.

## Dataset

The project uses the **IFEXA Healthcare BI Project Dataset** in Excel format.

Relevant fields include patient IDs, visit dates, age, visit count, state, department, service, revenue, cost, targets, and other healthcare performance attributes.

The data was transformed in Power Query before being modeled and visualized in Power BI.

## Dashboard Components

### Financial Performance

- Total Revenue
- Total Cost
- Total Profit
- Profit Margin
- Revenue Target
- Target Achievement

### Patient Analytics

- Total Patients
- Patients by Age Group
- New vs Returning Patients
- Patient Visit Trends

### Operational Performance

- Revenue by State
- Revenue by Department
- Revenue by Service
- Monthly Revenue Trends
- Revenue vs Target

### Executive Insights

Dynamic DAX measures provide narrative insights based on the current filter context, helping users understand performance rather than relying only on raw numbers.

## Data Preparation

Key transformations include:

- Cleaning and standardizing source data.
- Creating **New** and **Returning** patient classifications.
- Creating patient age groups.
- Preparing date fields for time-based analysis.
- Creating measures for revenue, cost, profit, margin, and target achievement.
- Using distinct patient counts where appropriate.

## Interactivity

Users can filter and explore the dashboard by:

- State
- Department
- Service
- Date/Month
- Patient characteristics

All relevant KPIs, charts, and executive insights update dynamically based on selections.

## Key DAX Concepts

The project demonstrates the use of:

- `SUM`
- `DISTINCTCOUNT`
- `DIVIDE`
- `CALCULATE`
- `SWITCH`
- `IF`
- `FORMAT`
- `SELECTEDVALUE`
- Time-intelligence functions
- Dynamic text measures

## Project Structure

```text
Healthcare-Performance-Patient-Analytics/
│
├── README.md
├── Dataset/
│   └── IFEXA_HealthCare_BI_Project_Dataset.xlsx
│
└── PowerBI/
    └── Healthcare_Performance_Patient_Analytics.pbix
