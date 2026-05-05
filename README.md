# Loan Insights - SQL Data Cleaning & Analysis

## Overview
EasyLoan provides personal, car, and mortgage loans across Canada, United Kingdom, and the United States. This project focuses on preparing and analyzing loan and client data to support business reporting and strategy decisions.

The goal is to ensure data quality, resolve missing values, and generate insights across geographic regions and loan types.

## Objectives
This project addresses four key tasks:

### 1. Data Cleaning (Client Table)
Clean and standardize the client table by:
- Validating data types
- Fixing inconsistent formats
- Removing or correcting invalid values

### 2. Handling Missing Values (Repayment Table)
Fill missing `repayment_channel` values using business rules:
- Repayments > 4000 → Bank Account
- Repayments < 1000 → Mail

### 3. US Online System Analysis
Extract loan data for US clients using the online contract system starting January 1, 2022.

Output:
- client_id
- contract_date
- principal_amount
- loan_type

### 4. Interest Rate Comparison
Compare average interest rates across countries by loan type.

Output:
- loan_type
- country
- avg_rate

## Tools Used
- SQL (PostgreSQL / MySQL compatible)
- Data cleaning techniques
- Aggregation queries

## Key Skills Demonstrated
- Data cleaning & validation
- Conditional logic in SQL (CASE WHEN)
- Joins and filtering
- Aggregations and grouping
- Business-driven analytics

## Files
- notebook.ipynb
