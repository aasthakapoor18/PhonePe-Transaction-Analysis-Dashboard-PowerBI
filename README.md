# PhonePe-Transaction-Analysis-Dashboard-PowerBI

## Project Overview
This project is an interactive Power BI dashboard built to analyze PhonePe transaction data and uncover insights related to transaction trends, user behavior, payment success rates, service usage, and demographic patterns.
The dashboard enables stakeholders to monitor key performance indicators (KPIs), identify popular services, track transaction growth, and understand customer segments through visual analytics.

##  Objectives
* Analyze overall transaction performance.
* Track monthly transaction trends.
* Measure payment success rates.
* Identify the most used PhonePe services.
* Understand user demographics and age groups.
* Compare weekday vs weekend transaction activity.
* Monitor month-over-month (MoM) growth.

## Dataset Information
The project uses two datasets:
### 1. All Users 
  Contains user-related information: 
     User ID
     User Name
     Age
     Join Date

### 2. All Transactions
  Contains transaction-related information:
    Transaction ID
    User ID
    Transaction Amount
    Service Category
    Service Type
    Payment Status
    Transaction Date

A relationship was created between both tables using **User ID**.

## Data Cleaning & Transformation

The following preprocessing steps were performed:
 1 Verified column quality and distribution.
 2 Removed duplicate records.
 3  Checked and corrected data types.
 4  Standardized categorical values.
 5  Created a Date Table using DAX.
 6 Built relationships between tables.
 7 Generated calculated columns for:
    Age Groups
    Weekday/Weekend Classification
    Month Names
    Quarter Information
    
## Key Performance Indicators (KPIs)
The dashboard includes the following KPIs:
* Total Transaction Value
* Total Transactions
* Success Rate %
* Total Users
* Month-over-Month (MoM) Growth %

##  Dashboard Visualizations
### Transaction Analysis
 Total Transaction Value by Month
 Total Transactions by Payment Status
 Month-over-Month Growth Analysis
 
### Service Analysis
 Transaction Value by Service
 Top 5 Users by Transaction Value

### User Demographics
User Distribution by Age Group
Weekend vs Weekday Transaction Analysis

### Interactive Features
Month Slicer
Payment Status Slicer
Tooltip for enhanced insights
Cross-filtering and drill-down interactions

##  Key Learnings
Through this project, I gained hands-on experience in:
* Building interactive Power BI dashboards.
* Creating relationships between datasets.
* Writing DAX measures and calculated columns.
* Designing KPI cards and business reports.
* Transforming raw data into meaningful insights.

### ⭐ If you found this project useful, feel free to explore the repository and provide feedback.
