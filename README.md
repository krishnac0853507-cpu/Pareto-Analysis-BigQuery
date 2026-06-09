# Pareto Analysis — BigQuery SQL

## Project Overview
Performed a Pareto (80/20) analysis on pet shop sales data 
to identify which customers drive the majority of revenue 
using Google BigQuery.

## Business Question
Which customers generate 80% of total revenue?

## Key Finding
- Top **57% of customers** generate **80% of total revenue**
- This slightly deviates from the classic 20/80 rule, 
  indicating a moderately concentrated customer base
- Actionable insight: Focus retention on top 150 out of 
  261 customers to protect 80% of revenue

## Tools & Technologies
- Google BigQuery (SQL)
- Google Cloud Platform

## SQL Techniques Used
- CTEs (Common Table Expressions)
- Window Functions (ROW_NUMBER, SUM OVER)
- Views (sales_v1 to sales_v4)
- DECLARE variable for dynamic threshold
- Aggregations and subqueries

## Files
| File | Description |
|------|-------------|
| `pareto_analysis_queries.sql` | All SQL queries |
| `pareto_final_result.csv` | Final Pareto output |
