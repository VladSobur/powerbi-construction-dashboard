
# Project Budget Performance & Cost Efficiency Dashboard (Power BI)
Construction-focused Power BI dashboard analyzing project budget performance, cost variance, and spending efficiency. 
The report highlights projects exceeding budget and provides visibility into financial performance across the portfolio.

<img width="1433" height="799" alt="dashboard-screenshot png" src="https://github.com/user-attachments/assets/4fe29d65-b016-46c3-b045-88be45ae0b4d" />

## Overview
This project is an end-to-end Power BI dashboard designed to analyze:

* Project budget vs actual spending
* Cost efficiency across projects
* Budget utilization and remaining budget
* Project-level financial performance

Key metrics included:

* Total Spend
* Total Budget
* Budget Variance
* Budget Used (%)
* Cost per Square Foot

The dashboard focuses on identifying cost overruns, monitoring budget usage, and evaluating financial efficiency across construction projects

## Business Problem
Construction companies often face:

* Budget overruns impacting profitability
* Limited visibility into project-level financial performance
* Difficulty identifying high-cost or inefficient projects
* Lack of centralized tracking for budget vs actual spending

This dashboard addresses key analytical questions:

* Are projects staying within allocated budgets?
* Which projects exceed budget and by how much?
* How does spending trend over time compared to budget?
* Which projects have the highest remaining budget?
* Which projects are the most expensive per square foot?

## Outcome

The analysis reveals that:

* Several projects exceed their allocated budgets, indicating cost control issues
* Spending trends show periods of rapid cost increase relative to budget allocation
* A small number of projects account for the largest share of total spend
* Cost per square foot varies significantly across projects, highlighting efficiency differences

The dashboard enables stakeholders to quickly identify financial risks, monitor budget utilization, and prioritize corrective actions.

## Key Features
### Financial KPIs
* Total Spend vs Total Budget
* Budget Variance ($)
* Budget Used %
* Average Completion %

### Performance Analysis
* Spend vs Budget trend over time
* Top 5 projects by spend
* Top 5 projects by remaining budget

### Risk Identification
* Projects exceeding budget
* Budget variance analysis

### Cost Efficiency
* Cost per Square Foot ($/Sq Ft)
* Top 5 most expensive projects by unit cost

### Interactive Filtering
* Project Type
* Project Manager
* Project Name
* Year / Time filtering

## Data Model
The dashboard is built using a star schema:
* **Fact Table**
  * `Fact_Cost`: stores actual costs and budget data
    
* **Dimension Tables**
  * `Dim_Project`: project attributes (type, manager, size, status)
  * `DateTable`: time intelligence (year, month, year-month)

## Key Measures (DAX)

Examples of core metrics:
* Total Spend
* Total Budget
* Budget Variance
* Budget Used %
* Budget Remaining %
* Cost per Sq Ft
* Project Count

## Tools & Technologies
* Power BI
* DAX (Data Analysis Expressions)
* Power Query (data transformation)
* Star Schema data modeling

## What I Demonstrate in This Project
* Building a clean and scalable data model
* Writing business-driven DAX measures
* Designing user-friendly and interactive dashboards
* Translating business requirements into data solutions
* Applying best practices in visualization and layout

## Outcome

This dashboard provides a clear view of project financial health, helping stakeholders:
* Identify overspending early
* Monitor budget utilization
* Compare project efficiency
* Make data-driven decisions


## Author

Vladimir Sobur
Data Analyst | Power BI | SQL

