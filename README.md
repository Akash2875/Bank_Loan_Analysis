# 🏦 Bank Loan Analysis

A data analytics project to monitor, assess, and visualize bank loan performance through KPIs and interactive dashboards.

## 📌 Project Overview

This project analyzes a bank's loan portfolio to track lending activity, evaluate loan quality, and uncover trends across regions, loan purposes, and borrower profiles. It is structured around two Business Requirements Documents (BRDs).

## 📊 BRD 1: Summary Dashboard

### Core KPIs

| KPI | Description |
|-----|-------------|
| **Total Loan Applications** | Total applications received in a given period + MTD tracking |
| **Total Funded Amount** | Total funds disbursed as loans + MTD tracking |
| **Total Amount Received** | Total repayments collected from borrowers + MTD tracking |
| **Average Interest Rate** | Average rate across all loans in the portfolio |
| **Average Debt-to-Income Ratio (DTI)** | Average DTI of borrowers to gauge financial health |

### Good Loan vs Bad Loan KPIs

**Good Loans**
- Good Loan Application Percentage
- Good Loan Applications (count)
- Good Loan Funded Amount
- Good Loan Total Received Amount

**Bad Loans**
- Bad Loan Application Percentage
- Bad Loan Applications (count)
- Bad Loan Funded Amount
- Bad Loan Total Received Amount

## 📈 BRD 2: Overview Dashboard (Charts)

| Chart | Type | Purpose |
|-------|------|---------|
| Monthly Trends by Issue Date | Line / Area Chart | Identify seasonality and long-term lending trends |
| Regional Analysis by State | Bar Chart | Spot regions with high activity and regional disparities |
| Loan Term Analysis | Donut Chart | Understand distribution of loans across term lengths |
| Employee Length Analysis | Bar Chart | Assess impact of employment history on loan applications |
| Loan Purpose Breakdown | Bar Chart | Visualize why borrowers seek financing |
| Home Ownership Analysis | Tree Map / Heat Map | See how home ownership affects loan applications and disbursements |

## 📁 Repository Structure

Bank-Loan-Analysis/
├── Bank_Loan_Analysis.ipynb
├── financial_loan.xlsx
└── Problem Statement Questions.pptx

## 🛠️ Tech Stack

- **Python** — Data processing and analysis
- **Pandas / NumPy** — Data manipulation
- **Matplotlib / Seaborn** — Data visualization
- **Jupyter Notebook** — Interactive analysis environment
- **Excel (.xlsx)** — Source data

## 📜 License

This project is for educational and analytical purposes.
