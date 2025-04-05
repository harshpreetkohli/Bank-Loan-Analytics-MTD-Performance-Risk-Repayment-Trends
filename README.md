# Bank Loan Analytics-MTD Performance-Risk-Repayment Trends (Power BI)

![Summary]()


## Overview
This Power BI dashboard provides comprehensive analytics for bank loan portfolios, tracking Month-to-Date (MTD) performance, risk assessment, and repayment trends. The project aims to help financial institutions make data-driven decisions by visualizing key loan metrics and identifying high-risk segments.

## Problem Statement
Financial institutions face critical challenges in:
1. **Risk Identification**  
   - 13.8% of loans ($65.5M) classified as "Bad Loans" with higher default risk
   - No clear visibility into DTI (13.3% avg) and interest rate (12.0% avg) correlations

2. **Performance Monitoring**  
   - Manual aggregation of MTD/MoM trends (15.8% MoM growth in applications)
   - Difficulty tracking $37.3M in Bad Loan repayments vs $435.8M Good Loans

3. **Decision Lag**  
   - Static reports delay responses to charged-off loans ($6.55M total)
   - No dynamic filters for loan purpose (74% debt consolidation) or geographic analysis


## Objectives
* Monitor MTD and Month-over-Month (MoM) loan performance trends
* Analyze risk distribution between Good Loans ($370.2M) and Bad Loans ($65.5M)
* Track repayment status (Current, Charged Off, Fully Paid) across loan portfolios
* Evaluate key metrics including:
  - Total Funded Amount ($435.8M)
  - Average Interest Rate (12.0%)
  - Average DTI Ratio (13.3%)
* Provide interactive filters for loan purpose, grade, and state analysis

## Key Features
- **Risk Segmentation**: Visual breakdown of Good vs Bad Loans
- **Performance Tracking**: MTD/MoM comparisons for all key metrics
- **Repayment Analysis**: Status tracking (32.1K Fully Paid vs 5.3K Charged Off)
- **Interactive Dashboard**: Drill-down capabilities by multiple dimensions

## Technical Specifications
* **Tools**: Power BI Desktop
* **Data Processing**: Power Query
* **Calculations**: DAX measures for dynamic metrics
* **Visualizations**: Custom charts and KPI indicators

## Dataset Overview
* Total Loan Applications: 38.6K
* Total Funded Amount: $435.8M
* Data Dimensions:
  - Loan Status
  - Risk Grade
  - Purpose
  - Geographic Location
  - Time Period
