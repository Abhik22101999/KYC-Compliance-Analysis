# Customer Identity Verification & Compliance Tracker

## Project Overview

This project analyzes customer KYC (Know Your Customer) verification data to monitor approval trends, rejection reasons, document verification status, and customer risk levels. The goal is to support compliance monitoring and improve the efficiency of the KYC verification process.

## Tools Used

* SQL Server
* Power BI
* Microsoft Excel
* DAX

## Dataset

The dataset contains 1,000 simulated customer KYC records with the following fields:

* Customer ID
* Customer Name
* Age
* State
* Document Type
* Verification Status
* Risk Level
* Rejection Reason
* Verification Time (Minutes)

## Project Workflow

1. Created and cleaned the KYC dataset in Excel.
2. Imported the dataset into SQL Server.
3. Performed SQL analysis to identify approval rates, rejection trends, and risk distribution.
4. Connected SQL Server data to Power BI.
5. Developed an interactive dashboard for compliance monitoring.

## SQL Analysis

The following analyses were performed:

* Verification status distribution
* Risk level distribution
* Top rejection reasons
* Document type analysis
* Average verification time

## Power BI Dashboard Features

* Total Customers KPI
* Approval Rate KPI
* Rejection Rate KPI
* Verification Status Analysis
* Risk Level Distribution
* Rejection Reason Analysis
* Document Type Distribution
* Interactive Filters and Slicers

## Key Insights

* Approval and rejection trends were identified across customer records.
* Name Mismatch and Expired Documents were among the major rejection reasons.
* Customer records were categorized into Low, Medium, and High Risk groups.
* Dashboard filters enable quick compliance monitoring and reporting.

## Repository Structure

Customer-Identity-Verification-Compliance-Tracker

├── Dataset
│   └── KYC_Customer_Dataset.xlsx

├── SQL Queries
│   └── KYC_Analysis.sql

├── Power BI Dashboard
│   └── KYC_Compliance_Dashboard.pbix

├── Dashboard Screenshots
│   └── dashboard.png

└── README.md

## Author

Abhishek Kumar

