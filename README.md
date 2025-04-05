# Bank Loan Analytics-MTD Performance-Risk-Repayment Trends (Power BI)

![Summary](https://github.com/harshpreetkohli/Bank-Loan-Analytics-MTD-Performance-Risk-Repayment-Trends/blob/main/Summary%20Bank%20Report.png)


## Overview
This Power BI dashboard provides comprehensive analytics for bank loan portfolios, tracking Month-to-Date (MTD) performance, risk assessment, and repayment trends. The project aims to help financial institutions make data-driven decisions by visualizing key loan metrics and identifying high-risk segments.

![Overview](https://github.com/harshpreetkohli/Bank-Loan-Analytics-MTD-Performance-Risk-Repayment-Trends/blob/main/Overview.png)

## Problem Statement

Financial institutions face several challenges in effectively managing and analyzing their loan portfolios. These issues often lead to missed opportunities, delayed decision-making, and increased exposure to financial risk. The key challenges this project aims to address include:

### 1. Risk Identification
- Difficulty in identifying high-risk loans due to limited visibility into borrower financial profiles.
- Lack of insights into the relationship between key risk factors such as debt-to-income ratios and interest rates.
- Inability to segment and monitor potentially risky accounts in real time.

### 2. Performance Monitoring
- Manual and time-consuming processes for tracking loan performance on a Month-to-Date (MTD) or Month-over-Month (MoM) basis.
- Fragmented data across systems hinders visibility into disbursements, repayments, and delinquencies.
- Challenges in comparing repayment trends between different loan products and customer segments.

### 3. Decision-Making Delays
- Static and outdated reports delay timely interventions for underperforming or charged-off loans.
- Lack of dynamic filters for analyzing data by loan type, customer category, region, or purpose.
- Missed early-warning indicators due to absence of interactive and real-time analytics tools.



## Objectives
* Monitor MTD and Month-over-Month (MoM) loan performance trends
* Analyze risk distribution between Good Loans and Bad Loans 
* Track repayment status (Current, Charged Off, Fully Paid) across loan portfolios
* Evaluate key metrics including:
  - Total Funded Amount 
  - Average Interest Rate 
  - Average DTI Ratio 
* Provide interactive filters for loan purpose, grade, and state analysis

## Key Features
- **Risk Segmentation**: Visual breakdown of Good vs Bad Loans
- **Performance Tracking**: MTD/MoM comparisons for all key metrics
- **Repayment Analysis**: Status tracking (33.2K Fully Paid vs 5.3K Charged Off)
- **Interactive Dashboard**: Drill-down capabilities by multiple dimensions

![Details](https://github.com/harshpreetkohli/Bank-Loan-Analytics-MTD-Performance-Risk-Repayment-Trends/blob/main/Details.png)

## Dataset Schema Overview

The dataset used in this project contains detailed information on individual loan applications and performance metrics. Below is a summary of the schema:

| Column Name            | Data Type      | Description |
|------------------------|----------------|-------------|
| `id`                   | INT (Primary Key) | Unique identifier for each loan record |
| `address_state`        | VARCHAR(50)    | U.S. state where the borrower resides |
| `application_type`     | VARCHAR(50)    | Type of application (Individual or Joint) |
| `emp_length`           | VARCHAR(50)    | Length of the borrower's employment |
| `emp_title`            | VARCHAR(100)   | Job title of the borrower |
| `grade`                | VARCHAR(50)    | Loan quality grade assigned by the lender |
| `home_ownership`       | VARCHAR(50)    | Borrower’s home ownership status (e.g., Rent, Own, Mortgage) |
| `issue_date`           | DATE           | Date the loan was issued |
| `last_credit_pull_date`| DATE           | Last date the borrower's credit was pulled |
| `last_payment_date`    | DATE           | Date of the most recent payment made |
| `loan_status`          | VARCHAR(50)    | Current status of the loan (e.g., Current, Charged Off, Fully Paid) |
| `next_payment_date`    | DATE           | Scheduled date for the next payment |
| `member_id`            | INT            | Unique identifier for the borrower |
| `purpose`              | VARCHAR(50)    | Stated purpose of the loan (e.g., Debt Consolidation, Home Improvement) |
| `sub_grade`            | VARCHAR(50)    | More granular classification within loan grade |
| `term`                 | VARCHAR(50)    | Loan term duration (e.g., 36 months, 60 months) |
| `verification_status`  | VARCHAR(50)    | Indicates if income was verified |
| `annual_income`        | FLOAT          | Declared annual income of the borrower |
| `dti`                  | FLOAT          | Debt-to-Income ratio |
| `installment`          | FLOAT          | Monthly installment amount |
| `int_rate`             | FLOAT          | Interest rate applied to the loan |
| `loan_amount`          | INT            | Total amount of loan approved |
| `total_acc`            | INT            | Total number of borrower’s credit accounts |
| `total_payment`        | INT            | Total amount paid to date (principal + interest) |


## Technical Specifications
* **Tools**: Power BI Desktop
* **Data Processing**: Power Query
* **Calculations**: DAX measures for dynamic metrics
* **Visualizations**: Custom charts and KPI indicators

## How to Use
1. Open the `.pbix` file in Power BI Desktop.
2. Update the data source to your data.
3. Refresh the data and start exploring interactive dashboards.
