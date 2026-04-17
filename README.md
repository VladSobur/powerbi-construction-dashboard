
# Project Budget Performance & Cost Efficiency Dashboard (Power BI)

<img width="1433" height="799" alt="dashboard-screenshot png" src="https://github.com/user-attachments/assets/4fe29d65-b016-46c3-b045-88be45ae0b4d" />

## Overview
This project is an end-to-end Power BI dashboard designed to analyze project financial performance for a construction company. 
The dashboard focuses on budget vs actual tracking, cost efficiency, and identifying high-risk or high-cost projects.

The goal of this project is to demonstrate my ability to transform raw operational data into actionable business insights 
using data modeling, DAX, and visualization best practices.

## Business Problem
Construction projects often suffer from budget overruns, inefficient cost allocation, and lack of visibility into project performance.
This dashboard answers key business questions:
* Are projects staying within budget?
* Which projects are overspending?
* Where is most of the budget being allocated?
* Which projects are the least cost-efficient ($/Sq Ft)?
* How does spending trend over time?

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

