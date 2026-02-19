# 🏦 Bank Loan Portfolio & Risk Analysis  
### End-to-End Banking Analytics Project

---

## 📌 Project Overview

This project analyzes a bank’s loan portfolio to evaluate lending performance, credit risk exposure, and repayment behavior. The objective was to design and implement a structured reporting solution that enables stakeholders to monitor loan applications, funding performance, repayment trends, and portfolio quality.

The solution simulates a real-world banking analytics workflow where data-driven insights support credit risk monitoring, operational efficiency, and strategic decision-making.

---

## 🎯 Business Objectives

- Monitor loan origination performance (MTD & MoM analysis)
- Evaluate funded vs received amounts
- Identify high-risk loan segments (Charged Off loans)
- Measure portfolio health using Good vs Bad Loan ratio
- Analyze borrower characteristics (State, Grade, Employment Length, Purpose)
- Track interest rate and DTI impact on loan performance
- Provide a consolidated executive-level reporting dashboard

---

## 📊 Dataset Information

**Source:** Loan application dataset (financial_loan.csv)

The dataset includes:

- Loan Amount  
- Funded Amount  
- Total Payment (Received Amount)  
- Interest Rate  
- Debt-to-Income Ratio (DTI)  
- Loan Status (Fully Paid, Current, Charged Off)  
- Term (36 / 60 months)  
- Employment Length  
- Loan Purpose  
- Home Ownership  
- State  

---

## 🏗️ Project Workflow & Architecture

### 1️⃣ Domain Understanding
Studied core banking concepts including:
- Credit risk classification
- Loan lifecycle (Application → Approval → Repayment → Default)
- DTI evaluation
- Portfolio risk exposure
- Profitability tracking

---

### 2️⃣ Data Preparation (SQL Server)

- Imported dataset into SQL Server
- Performed data validation and cleaning
- Built KPI queries using:
  - GROUP BY
  - CASE statements
  - Conditional filtering
- Created Month-To-Date (MTD) and Previous Month-To-Date (PMTD) logic
- Segmented Good vs Bad Loans based on Loan Status

All KPI logic was documented separately for traceability and clarity.

---

### 3️⃣ Data Modeling (Power BI)

- Built structured data model
- Created calculated measures
- Designed dynamic MTD vs MoM comparisons
- Implemented filtering using slicers
- Structured relationship model for performance optimization

---

### 4️⃣ Dashboard Structure

The report is divided into three reporting layers:

---

### 🔹 Summary Dashboard

Executive-level KPIs:

- Total Loan Applications
- Total Funded Amount
- Total Received Amount
- Average Interest Rate
- Average DTI
- Good Loan vs Bad Loan Ratio
- Loan Status Performance Table

This page provides portfolio health visibility.

---

### 🔹 Overview Dashboard

Analytical breakdown including:

- Loan Applications by Month
- State-wise Loan Distribution
- Loan Term Segmentation
- Employment Length Analysis
- Loan Purpose Analysis
- Home Ownership Distribution

This page supports trend and segmentation analysis.

---

### 🔹 Details Dashboard

- Transaction-level data view
- Drill-down capability
- Loan-level performance monitoring

This page supports operational-level analysis.

---

## 📈 Key Insights

- 86% of the portfolio consists of performing loans (Fully Paid + Current)
- Approximately 14% of loans are classified as high-risk (Charged Off)
- Loan applications show consistent month-over-month growth
- 60-month term loans dominate portfolio share
- Higher DTI segments indicate elevated risk exposure
- Funded amount vs received amount reflects overall portfolio profitability

---

## 🛠 Tools & Technologies Used

- **SQL Server** (Aggregation, Conditional Logic, KPI Calculation)
- **Power BI** (Data Modeling, DAX, Dashboard Design)
- **Excel** (Initial data inspection)
- Banking domain documentation for business alignment

---

## 💼 Business Impact

This project demonstrates how structured analytics can:

- Improve credit risk visibility
- Support portfolio monitoring
- Enable proactive risk mitigation
- Assist decision-makers in lending strategy optimization
- Provide executive-ready performance reporting

---

## 📌 Analyst Positioning

This project reflects practical experience in:

- KPI-driven reporting
- Portfolio risk segmentation
- Business-oriented data modeling
- End-to-end analytics workflow (SQL → BI → Insight Delivery)

It demonstrates analytical thinking aligned with real-world banking analytics practices.

---
## 📊 Dashboard Screenshots

### Bank Loan Report Summary 
![Bank loan_summary_dashboard](https://github.com/user-attachments/assets/3abeea65-fbc6-43d0-becc-88d76e6b4f4a)

### Bank Loan Report Overview
![Bank loan_overveiw_dashboard](https://github.com/user-attachments/assets/a7518240-4b0d-49bf-8d53-4903a60f2a38)

### Bank Loan Report Details
![Bank loan_Detailes_dashboard](https://github.com/user-attachments/assets/288a9f36-95e6-4550-b557-86448cd160cb)


---


