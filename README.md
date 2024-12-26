# Credit_Card_Financial_Dashboard

## Project Objectives

To develop comprehensive credit card weekly dashboard that provides real-time insights into key performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations effectively.

## Dataset 

Financial dataset

## Steps 

### Credit Card Transection Report

1. Import Data From SQL Database.
 * Prepare CSV File
 * Create table in SQL
 * Import CSV into SQL
2. Data Processing and DAX Queries
  * Grouped customers by age and income to derive insights.
  * Calculated Revenue with annual fees, total transaction amount and interest earned.
  * Derived week numbers using DAX Query.
  * Calculated week by week change in revenue ( (current_week_revenue - previous_week_revenue) / previous_week_revenue ).
3. Create Dashboard and derive insight
  *  calculated sum of revenue, total transaction amount and interest earned by card category.
  *  visualised revenue by customer's job, expenditure type, education level, card type, and chip used.
  *  visualised revenue by quarters.
  *  added cards to show important KPIs.
  *  added slicer to select week.
  *  used tree map to provide categories (Quarter, gender, card type, income group).

