# 🏦 Bank Transaction Analysis – Power BI Dashboard

An end-to-end Power BI project analyzing real-time bank transaction data for **State Bank of Indiana**, covering customer behavior, transaction patterns, fees, taxes, and risk across states, segments, and demographics.

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Tool](https://img.shields.io/badge/Tool-Power%20BI-F2C811?logo=powerbi&logoColor=black)
![Language](https://img.shields.io/badge/DAX-Data%20Modeling-blue)

---

## 📌 Project Overview

This dashboard provides real-time insights into transactions, customers, and risk for a banking institution. It enables stakeholders to monitor key financial KPIs, drill into transaction-level details, and analyze trends across time, geography, demographics, and customer segments — with dynamic filtering by year, occupation, and merchant category.

---

## 📊 Dashboard Pages

### 1. Overview Analysis
- **KPI Cards:** Total Amount (₹21.7M), Total Transactions (2K), Avg Transaction Value (₹9.17K), Total Fees (₹33.9K), Total Tax (₹6.1K) — each with YoY % comparison
- **Total Amount by Month** — area trend chart highlighting seasonal peaks (Apr & Jul)
- **Total Amount by Transaction Status** — donut chart (Success: 85.2%, Failed: 10.0%, Pending: 4.8%)
- **Total Amount by Customer Segment** — Retail, Premium, SME, Corporate, Wealth
- **Total Amount by State** — top states by transaction value (Maharashtra, Gujarat, Tamil Nadu, etc.)
- **Transaction Type Analysis** — matrix breakdown of Amount, Fees, Tax & Transaction count by type (Loan EMI, Transfer, Deposit, Investment, etc.)
- **Total Amount by Gender** — Male vs Female split

### 2. Transactions (Detail View)
- Transaction-level table with Transaction ID, Date, Customer Name, Type, Status, Gender, Customer Segment, State, Total Amount, Fees & Tax
- Fully filterable by Year, Dynamic Metric, Occupation, and Merchant Category
- Supports row-level drill-through for auditing and deep-dive analysis

---

## ⚙️ Features
- 🔄 **Dynamic Metric Switching** – toggle between Total Amount, Fees, Tax, etc. using a DAX-driven parameter
- 📅 **Year & Slicer-based Filtering** – Year, Occupation, Merchant Category
- 📈 **YoY Growth Indicators** on every key metric
- 🧮 **Custom DAX Measures** for KPI calculations, dynamic titles, and conditional formatting
- 🎨 Clean, corporate-style UI themed for a banking dashboard

---

## 🗂️ Repository Contents

| File | Description |
|------|-------------|
| `Bank Transaction Analysis.pbix` | Main Power BI dashboard file |
| `Bank Loan Analysis DAX.xlsx` | DAX measures and calculation documentation |
| `Bank Transaction Analysis pdf.pdf` | Exported project report / presentation |
| `finance_transactions.csv` | Raw transaction-level dataset |
| `customers.csv` | Raw customer demographic dataset |

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** – data modeling, visualization & dashboard design
- **DAX** – KPI calculations, dynamic measures, YoY comparisons
- **Power Query** – data cleaning & transformation
- **Excel / CSV** – raw data sources

---

## 🔍 Key Insights
- Retail customers contribute the largest share of total transaction value (₹11.9M)
- Maharashtra leads state-wise transaction volume at ₹3.3M
- 85.2% of transactions complete successfully, while ~15% fail or remain pending — a potential area for process improvement
- Loan EMI transactions generate the highest fees and tax among all transaction types
- Transaction value is nearly evenly split by gender (50.9% Female / 49.1% Male)

---

## 📷 Dashboard Preview

**Overview Analysis**
![Overview Analysis](https://raw.githubusercontent.com/abhisheknirmal02-lab/Bank-Transaction-Analysis-/main/Overview%20Analysis.png)

**Transactions View**
![Transactions](https://raw.githubusercontent.com/abhisheknirmal02-lab/Bank-Transaction-Analysis-/main/Transaction.png)

---

## 👤 Author

**Abhishek Nirmal**
Data Analyst | Power BI • SQL • Python • Excel
🔗 [LinkedIn](https://www.linkedin.com/in/abhishek-nirmal-3b6325370/) | [GitHub](https://github.com/abhisheknirmal02-lab)

---

⭐ If you found this project useful, consider giving it a star!
