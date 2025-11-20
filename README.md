💼 IT Expenditure Analysis – Budget vs Forecast vs Actual

This project analyzes an enterprise IT financial dataset (81K+ records) to understand how well the organization manages its IT budget across Business Areas, Countries, IT Areas, and Cost Element Groups.
The analysis uncovers whether the company is overspending, underspending, or misaligned with its planned and forecasted budgets.

🚀 Objective

The goal of the analysis is to:

Evaluate Actual vs Plan vs Forecast spend

Identify variance patterns across different business dimensions

Determine whether overspending is occurring

Understand underspending, budget utilization, and execution delays

Provide insights to improve future financial planning and performance

📂 Dataset Overview

The dataset consists of 81,000+ IT financial transactions, containing:

Date (Month)

Business Area

Region and Country

IT Area & IT Sub Area

Cost Element Name

Cost Element Group & Sub Group

Actual Spend

Forecast Spend

Planned Budget

After cleaning and grouping, the dataset was aggregated into ~25K summary records for meaningful financial reporting.

📊 Key Metrics Calculated
1. Variance Metrics

Actual – Plan

Actual – Forecast

Forecast – Plan

Variance % (Safe formula avoiding division by zero)

These measures quantify financial performance across all business dimensions.

🔍 Major Analyses Performed
1. Overall Spend Comparison

Total Actual Spend

Total Forecast Spend

Total Planned Budget

2. Variance Insights

Variance by Business Area

Variance by Country

Variance by Cost Element Group

Variance by IT Area

3. Trend Analysis

Month-wise Actual vs Forecast vs Plan trend line

4. Budget Utilization

Budget Utilization (%) by Country

Identification of highest and lowest utilization regions

5. Heatmap Analysis

Underspend Heatmap across Business Area × Cost Element Group

6. Top 10 Lowest Utilization Areas

Highlighting worst financial execution units

7. Waterfall Chart

A waterfall illustrating:

Plan → Forecast → Actual
Shows how the budget expectation breaks down into real spending.

🧠 Key Findings

The organization had zero overspending anywhere in the dataset.

All variances showed significant underspending across departments.

Actual spend was far below both Plan and Forecast.

Forecast adjustments were minimal and did not reflect real execution delays.

Some countries (e.g., Spain) showed strong budget discipline.

Most IT Areas and Cost Groups suffered from large execution gaps.

Budget planning was over-optimistic, and project execution was delayed.

🎯 Conclusion

The company does not have an overspending problem.
It has a systemic underspending and execution problem, where:

Budgets are overestimated

Forecasts are inaccurate

Projects are delayed or not executed

Actuals never catch up to expectations

Financial planning, forecasting discipline, and project execution processes need improvement to ensure better alignment between Plan → Forecast → Actual.

🛠️ Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter / Colab

Data Cleaning & Transformation

Exploratory Data Analysis (EDA)

Variance & Trend Modeling

Visualization and Storytelling

📘 How to Use

Load the dataset into the notebook.

Run data cleaning and numeric conversions.

Group the data using key financial dimensions.

Generate variance metrics and plots.

Interpret insights using the visuals and tables.
