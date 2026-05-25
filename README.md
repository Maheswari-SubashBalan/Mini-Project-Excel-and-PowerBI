# 🏦 Bank Customer Financial Insights & Analysis

## 📌 Project Overview
Analysed bank customer financial data to derive meaningful insights about customer demographics, income patterns, loan behaviour, and account status using Excel, Power Query and Power BI.

---

## 🛠️ Tools Used
| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data Cleaning & Preprocessing |
| Power Query | Data Transformation |
| Power BI | Dashboard & Visualization |

---

## 📂 Dataset
- **Records:** 500 Bank Customers
- **Cities:** Trichy, Salem, Chennai, Coimbatore, Madurai
- **Columns:** Customer_ID, Name, City, Age, Age Group, Gender, Account Balance, Loan Amount, Monthly Income, Income Category, Account Type, Status

---

## 🧹 Data Cleaning (Excel)
- ✅ Removed Duplicates
- ✅ Standardized Gender values using Find & Replace
- ✅ Created Name column using CONCATENATE formula
- ✅ Filled missing values using IF + AVERAGE and AVERAGEIF
- ✅ Created Pivot Tables for summary insights

---

## ⚙️ Data Transformation (Power Query)
- ✅ Added Age Group column — Young / Middle Age / Senior
- ✅ Added Income Category column — Low / Medium / High Income
- ✅ Fixed Data Types for all columns

---

## 📊 DAX Measures (Power BI)
- Total Customers = COUNT(Transformation[Customer_ID])
- Average Loan Amount = AVERAGE(Transformation[Loan Amount])
- Average Monthly Income = AVERAGE(Transformation[Monthly Income])
- Active Customers = CALCULATE(COUNT(Transformation[Customer_ID]), Transformation[Status] = "Active")

---

## 📈 Dashboard Visualizations
- 🃏 KPI Cards — Total Customers, Avg Loan, Avg Income, Active Customers
- 🥧 Pie Chart — Gender Distribution
- 📊 Bar Chart — Age Group vs Loan Amount
- 📊 Clustered Column — Income Category vs Account Balance
- 🍩 Donut Chart — Account Type Distribution
- 🗺️ Map Chart — City wise Customer Count
- 🔻 Funnel Chart — Income Category wise Count
- 🔵 Scatter Chart — Monthly Income vs Account Balance
- 📈 Line Chart — Age vs Account Balance
- 📉 KPI Visual — Account Balance vs Loan Amount
- 🔽 Slicers — Gender, Age Group, Income Category, Status

---

## 💡 Key Insights
- 244 Active customers out of 500 (48.8%)
- Middle Age group carries the highest loan amount
- High Income customers have higher account balances
- Positive correlation between Monthly Income and Account Balance
- Savings is the most popular account type (37.4%)

---

## 📁 Repository Structure
| File | Description |
|------|-------------|
| Bank Customers Financial Analysis.xlsx | Cleaned Excel dataset |
| Bank Customers Financial Analysis.pbix | Power BI dashboard file |
| Dashboard.png | Final dashboard screenshot |
| README.md | Project documentation |

---

## 🖥️ Dashboard Preview
![Dashboard](Dashboard.png)

---

## 🙋 Author
**Maheswari M**
- GitHub: (https://github.com/Maheswari-SubashBalan/Mini-Project-Excel-and-PowerBI)
