# 📊 Stocks Volume Analysis Dashboard

## 📌 Project Overview

This project analyzes **stock trading volume trends** between **2021 and 2023** using data fetched from **Yahoo Finance**.  
The goal of the dashboard is to answer the following business question:

> **How does the stock trading volume look across the years 2021–2023?**

The dashboard provides stakeholders with a high-level overview of historical trading activity to identify patterns, spikes, and overall volume behavior across the selected timeframe.

---

## 📂 Data Sources

1. **`fact_stocks` Table**  
   - Source: : Yahoo Finance API  
   - Contains historical stock market data including:
     - Date
     - Open
     - High
     - Low
     - Close
     - Volume

2. **`dim_date` Table**  
   - Source: Generated through Microsoft Excel  
   - Contains structured calendar data (Year, Month, Quarter, etc.)
   - Used to enable time-based analysis and aggregation

---

## 🛠 Steps & Methodology

### 1️⃣ Business Scenario Definition
- Business case was given

---

### 2️⃣ Data Wrangling

**Data Gathering**
- Pulled historical stock data from Yahoo Finance API.
- Imported date dimension data from Excel.

**Data Assessment**
- Checked for:
  - Missing values
  - Data type inconsistencies
  - Date alignment issues

**Data Cleaning**
- Standardized date formats.
- Ensured correct relationships between `fact_stocks` and `dim_date`.
- Removed or handled null values.

---

### 3️⃣ Data Analysis (Descriptive Analysis)

Performed descriptive analytics to:
- Examine yearly volume trends.
- Compare volume distribution across months and years.
- Identify peak trading periods.
- Highlight significant spikes or drops in activity.

---

### 4️⃣ Results Sharing

The final results were delivered through:

- 📊 Tableau Interactive Dashboard  
- 📈 PowerPoint Presentation (Stakeholder-ready insights)

---

## 🎨 Design Screenshots

![DB Sketch](https://github.com/user-attachments/assets/35b6a0f7-b93e-4f42-a330-0942fcdd00bb)

---

## 📊 Dashboard Screenshots

<img width="1624" height="829" alt="Financial Dashboard" src="https://github.com/user-attachments/assets/3b258a5a-0d2e-4ccc-9553-a71eb07e22d4" />

---

## 🔎 Key Insights

<img width="1288" height="723" alt="2026-02-22 18_24_35-Financial Dashboard Overview pptx - PowerPoint" src="https://github.com/user-attachments/assets/e95f2c72-4f25-40be-8493-5fc9e738fc92" />

---

## 🌐 Live Dashboard

🔗 **Access the Live Dashboard Here:**  

[Tableau Dashboard](https://public.tableau.com/views/FinancialDashboardProject_17717036408760/FinancialDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## ⚠️ Assumptions & Limitations

### Assumptions
- Data retrieved from Yahoo Finance API is accurate and reliable.
- Stakeholders require only a high-level historical overview.

### Limitations
- No predictive or forecasting models were implemented.
- Analysis limited to 2021–2023.
- External macroeconomic factors were not incorporated.
- Manual data refresh process (no automation implemented).

---

## 🚀 Future Work

- Implement workflow automation:

![Automation Workflow](https://github.com/user-attachments/assets/2f1b4ca2-5a1f-44f5-b3f5-1e4019da98a2)

---

> This project provides a structured and visual exploration of stock trading activity trends to support data-driven decision-making.
