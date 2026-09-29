# 🏥 Hospital Financial Performance & Cash Flow Dashboard

## 📌 Project Overview

This project analyzes hospital financial performance across patient payments, insurance claims, government reimbursements, operational expenses, outstanding receivables, revenue, and profitability.

The solution combines **Power BI** for interactive business dashboards with **Python** for data understanding, validation, cleaning, and exploratory analysis.

The goal is to provide hospital management with a unified view of cash inflows, cash outflows, financial trends, outstanding balances, and reimbursement performance so that financial gaps and payment delays can be identified more quickly.

## 🎯 Business Objectives

The main objectives of this project are to:

- Monitor overall hospital financial performance
- Analyze cash inflows and cash outflows
- Track patient-payment collections
- Analyze insurance reimbursements
- Analyze government reimbursements
- Monitor outstanding receivables
- Compare revenue and expense trends
- Identify delayed payments and financial gaps
- Track profitability and monthly financial performance
- Support data-driven financial decision-making

## 📊 Data Model

The Power BI data model contains the following core tables:

- `clean_cash_outflows`
- `clean_government`
- `clean_insurance`
- `clean_monthly_financial`
- `clean_outstanding`
- `clean_patient_payments`
- `Date_Dimension`

These tables provide a consolidated structure for analyzing the hospital's major financial activities.

## 📈 Analysis Areas

### 💰 Cash Flow Analysis

Tracks money flowing into and out of the hospital and helps identify potential cash-flow gaps.

### 👤 Patient Payment Analysis

Examines patient-payment collections and payment-related patterns.

### 🛡️ Insurance Analysis

Analyzes insurance-related claims and reimbursements.

### 🏛️ Government Reimbursement Analysis

Tracks government-related reimbursement activity and financial contribution.

### 📋 Outstanding Receivables

Monitors unpaid or pending balances to help identify collection risks and delayed payments.

### 📅 Monthly Financial Performance

Analyzes financial performance over time, including revenue, expenses, cash flow, and profitability.

### 📉 Expense Analysis

Reviews operational cash outflows to understand major expense areas.

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Excel**
- **Data Modeling**
- **Data Cleaning**
- **Exploratory Data Analysis**
- **Financial KPI Analysis**
- **Business Intelligence**

## 📁 Repository Structure

```text
Hospital-Financial-Performance-Dashboard/
│
├── README.md
├── 01_Hospital_Financial_Analysis.ipynb
├── PROJECT_OVERVIEW.md
├── DATA_MODEL.md
├── requirements.txt
├── .gitignore
│
├── data/
│   └── README.md
│
└── screenshots/
    └── README.md
