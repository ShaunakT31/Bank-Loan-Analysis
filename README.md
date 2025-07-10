# Bank Loan Report (SQL + Power BI)

## Project Overview

This project presents a comprehensive analysis of bank loan data using SQL and Power BI. The objective is to provide detailed insights into the bank's lending performance, borrower profiles, and loan outcomes. The Power BI report is structured into three dashboards: **Summary**, **Overview**, and **Details**.

---

## Objectives

- Analyze and track key loan performance metrics over time
- Classify and compare Good Loans (Fully Paid or Current) vs. Bad Loans (Charged Off)
- Identify trends based on loan purpose, term, region, borrower employment, and home ownership
- Support data-driven decision making through visual storytelling and clear KPIs

---

## Dashboards

### 1. Summary Dashboard
Focuses on high-level KPIs, including:
- Total Loan Applications (overall and month-to-date)
- Total Funded Amount and Total Amount Received (overall and MoM)
- Average Interest Rate and Debt-to-Income Ratio
- Good Loan vs. Bad Loan metrics based on loan status
- Loan Status Grid View for performance comparison

### 2. Overview Dashboard
Visual breakdowns by different loan attributes, including:
- Monthly trends (line chart)
- State-wise performance (filled map)
- Loan terms (donut chart)
- Employment length (bar chart)
- Loan purpose (bar chart)
- Home ownership status (tree map)

### 3. Details Dashboard
A detailed tabular view of all loan records and fields, supporting deep-dive analysis.

---

## Tools Used

- **SQL** (for data querying and transformation)
- **Power BI** (for data modeling and dashboard creation)

---

## Dataset Information

The dataset includes anonymized records of loan applications, disbursed amounts, repayment details, borrower employment and income information, home ownership status, and loan status.

Key fields include:
- `Loan_Amount`, `Total_Payment`, `Int_Rate`, `DTI`, `Term`
- `Issue_Date`, `Loan_Status`, `Purpose`, `Emp_Length`, `Address_State`
- `Home_Ownership`, `Annual_Income`, `Verification_Status`, etc.

A full list of field definitions is provided in the **Data_Terminologies.pdf**.

---

## Repository Contents

- `Problem Statement.pdf` – Description of the business problem and reporting objectives
- `Terminologies Used in Data.pdf` – Definitions and usage of fields in the dataset
- `QueryDocument.pdf` – Full list of SQL queries used for metrics and visuals
- `Images/` – Screenshots of the three report dashboards (Summary, Overview, Details)

---

## How to Use

1. Review the `Problem Statement.pdf` to understand the reporting scope
2. Check `QueryDocument.pdf` to see how metrics were derived
3. Explore the screenshots to visualize the final outputs
4. All KPIs and charts are interactive in the actual Power BI report (not included here due to file size)

---

## Author

Created by [Your Name] as part of a data analytics portfolio project.
