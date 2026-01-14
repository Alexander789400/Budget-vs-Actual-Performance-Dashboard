# Budget-vs-Actual-Performance-Dashboard

An end-to-end financial analysis and dashboard project built using WPS Spreadsheet / Excel concepts to compare Budget vs Actual spending, identify over-budget areas, and deliver management-level insights through KPIs and interactive visuals.

Project Objective :

Compare budgeted vs actual expenses

Analyze variance and variance %

Identify over-budget departments, regions, and categories

Build an interactive dashboard for decision-making

Dataset Overview :

[Dataset Link](https://www.kaggle.com/datasets/kennathalexanderroy/budget-vs-actual-financial-dataset)

Type: financial dataset

Rows: 10,000

Time Period: 3 continuous years (2021–2023)

Columns: 8

Key Fields:

Transaction ID

Date

Department

Category

Region

Budget Amount

Actual Amount

Payment Method

Data Cleaning & Preparation :

Removed 10 duplicate records

Deleted rows with missing Transaction IDs

Created helper columns:

Month

Year

Variance

Variance %

Status (Over Budget / Under Budget)

Used Power Query and Excel formulas

Key Calculations :

Variance = Budget Amount − Actual Amount

Variance % = (Variance / Budget Amount) × 100


Business Logic:

Positive Variance → Under Budget

Negative Variance → Over Budget

Dashboard Features :

KPI Cards

Total Budget

Total Actual

Total Variance

Variance %

10+ Charts, including:

Monthly Budget vs Actual

Monthly Variance % Trend

Department-wise Variance

Category-wise Budget vs Actual

Region-wise Variance

Top 5 Over-Budget Departments

Interactive Slicers

Year

Department

Region

Category

Key Insights :

Overall variance improved from -0.14% (2021) to -0.10% (2023)

Peak actual spend months:

2021: May

2022: December

2023: April

All departments are over budget

Highest variance: Marketing (-21%)

Highest actual spend: HR

All regions are over budget

Highest variance: East (-22%)

Highest actual spend: Central

All categories are over budget

Highest overspend: Utilities

Conclusion :

Budget efficiency has slightly improved over time

Overspending persists across departments, regions, and categories

Marketing, East region, and Utilities drive major budget deviations

Dashboard enables fast, data-driven financial decisions

Recommendations :

Tighten budget controls for Marketing and Utilities

Monitor high-spend months proactively

Enforce region-wise spending limits

Use the dashboard for monthly variance reviews

🛠 Tools & Skills Used

WPS Spreadsheet / Excel

Power Query

Pivot Tables & Calculated Fields

Conditional Formatting

Dashboard Design

Financial & Variance Analysis

Use Cases :

Financial reporting

Budget monitoring

Management dashboards

Resume & portfolio project

👤 Author

Alexander Roy
