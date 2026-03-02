# Revenue-Commission-Settlement-Analytics
Excel-based Revenue, Commission &amp; Settlement Analytics Dashboard with automated financial validation and exception monitoring.
📊 Edviron – Revenue, Commission & Settlement Analytics Dashboard
📌 Project Overview

This project focuses on building a complete Revenue and Settlement Analytics solution for Edviron using Microsoft Excel. The objective was to design a structured financial model to compute partner commissions, ERP revenue, Edviron margins, and settlement exposure while implementing automated validation controls.

The solution includes revenue computation logic, partner-level performance analysis, gateway contribution tracking, and exception monitoring mechanisms.

🎯 Business Objectives

Calculate ERP and Edviron revenue accurately

Analyze partner and gateway performance

Monitor settlement exposure (SUCCESS / PENDING / FAILED)

Detect pricing inconsistencies and negative margin transactions

Build an interactive executive dashboard

🧮 Revenue Logic Implemented

Revenue calculations were implemented using normalized pricing logic:

Partner Absolute Pricing

Merchant Absolute Pricing

Edviron Buying Cost

ERP Revenue

Edviron Net Revenue

Edviron Gross Revenue

Revenue validation applied only for SUCCESS transactions to ensure accurate reporting.

🚨 Exception Monitoring (Bonus Enhancement)

Advanced financial validation logic was implemented:

Negative Margin Flag
Identifies transactions where Edviron Net Revenue is below zero.

Pricing Error Flag
Detects cases where Merchant pricing is lower than Partner pricing.

These controls help prevent revenue leakage and pricing structure errors.

📈 Reports Created

Daily / Weekly / Monthly Revenue Summary

Partner-wise Performance Analysis

Gateway & Payment Method Analysis

Pending vs Settled Exposure Report

📊 Dashboard Features

Total Transactions

Total GMV

ERP Revenue

Edviron Net Revenue

Edviron Gross Revenue

Unique Users

Pending Exposure

Revenue Split Visualization

Time Trend Analysis

Gateway Contribution Chart

Payment Method Mix

Interactive elements include:

PivotTables

PivotCharts

Slicers

Timeline Filters

KPI Cards

🛠 Tools & Technologies Used

Microsoft Excel

Power Query

PivotTables

PivotCharts

Slicers & Timeline

VBA (for automation)

File Format: .xlsm

💡 Key Business Insights

Revenue margins remained consistent

No negative margin transactions detected

Gateway concentration observed

Payment frequency largely single-use

Settlement exposure monitored dynamically

🚀 Future Improvements

Automated reconciliation module

Scenario stress testing

Exception summary dashboard

UI enhancement

👤 Author

Vishal [Your Full Name]
Revenue & Data Analytics Enthusiast
March 2026
