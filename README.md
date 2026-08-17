# 📊 Data Analytics & Business Intelligence — Task 4
### AdventureWorks Sales — Star Schema, Channel & Profitability Analysis

`Data Model: Star Schema` &nbsp;•&nbsp; `DAX: Calculated Measures` &nbsp;•&nbsp; `Power BI: Executive Dashboard`

This repository contains a full star-schema sales analysis built on the AdventureWorks dataset — covering dimensional data modeling, DAX measures, channel and profitability analysis, an interactive Power BI dashboard, and a business insights report.

---

## 🏢 Internship Details

| | |
|---|---|
| **Company** | Maincrafts Technology ([www.maincrafts.com](https://www.maincrafts.com)) |
| **Program** | Data Analytics & Business Intelligence Internship |
| **Task** | Task 4 — Star Schema Data Modeling, DAX Measures & Channel Profitability Analysis |
| **Intern** | Prince Kumar — MBA (Business Analytics), Delhi School of Management, DTU |
| **Contact (Company)** | hr@maincrafts.com |

This task steps up from Tasks 1–3 by moving from a single flat sales table into a **proper dimensional model** — a Sales fact table connected to Date, Product, Customer, Reseller, and Sales Territory dimensions — and introduces DAX-based calculated measures in Power BI.

---

## 📁 Repository Structure

| File | Description |
|---|---|
| `AdventureWorks_Sales.xlsx` | Star-schema workbook — Sales fact table plus Date, Product, Customer, Reseller, Sales Territory, and Sales Order dimension/bridge tables |
| `Task_4_Dashboard.pbix` | Power BI dashboard with the full data model, calculated DAX measures, and interactive visuals |
| `Task_4_Star_Schema_Model.png` | Data model diagram showing fact-to-dimension relationships |
| `Task_4_Dax_Measures_Screenshot.png` | Screenshot of key DAX measures used in the dashboard |
| `Business_Insights_Report_Task4.pdf` | Final business insights report with channel, regional, and category profitability findings |

---

## 🎯 Objective

- Build a proper star-schema data model (fact table + conformed dimensions)
- Write DAX measures for sales, profit, margin, and channel-level KPIs
- Analyze profitability by sales channel, region, category, and product
- Identify and explain profitability gaps across the reseller network
- Deliver a business insights report translating the model into strategic recommendations

---

## 🛠️ Tools Used

- **Power BI** — star schema data modeling, relationships, DAX calculated measures
- **Microsoft Excel** — source data review and validation across fact/dimension tables
- **DAX** — Sales, Profit, Margin %, and channel/category-level calculated measures

---

## 📈 Key Metrics

| Metric | Value |
|---|---|
| Total Sales | **$109,809,274.20** |
| Total Profit | **$12,551,366.25** |
| Overall Profit Margin | 11.4% |
| Order Lines | 121,253 |
| Distinct Sales Orders | 31,455 |
| Customers / Active Resellers | 18,485 / 633 |
| Analysis Period | FY2018 – FY2020 |

---

## 🔍 Key Insights

- **Channel profitability gap (headline finding):** Internet sales are only 26.7% of revenue but generate **96.3%** of total company profit (41.1% margin). The Reseller channel — 73.3% of revenue — returns almost nothing (0.6% margin). Every dollar of Internet sales is worth ~70x more in profit than a dollar of Reseller sales.
- **Reseller network health:** 334 of 633 active resellers (52.8%) are **losing** the company money, collectively -$2.17M — nearly 5x the entire channel's reported net profit. Even 3 of the top 5 resellers by sales volume are unprofitable.
- **Region:** Southwest (US) is the largest market by sales, but Australia is the most profitable by margin (33.6%) — over 3x Southwest's margin.
- **Category:** Bikes drive 86% of sales at 11.1% margin; Accessories are the smallest category but the most profitable at 49.9% margin. Touring Frames and Jerseys are the only two sub-categories operating at a net loss.
- **Product:** The Mountain-200 line sweeps the top 5 products by sales, reinforcing Mountain Bikes as the strongest combination of volume and margin.
- **Trend:** Sales more than doubled from FY2018 to FY2020, but margin slipped slightly — growth is being driven more by low-margin Reseller volume than by the more profitable Internet channel.

Full breakdown, tables, and strategic recommendations are in [`Business_Insights_Report_Task4.pdf`](./Business_Insights_Report_Task4.pdf).

---

## 🗄️ How to Reproduce

1. Open `AdventureWorks_Sales.xlsx` to review the fact and dimension tables.
2. Open `Task_4_Dashboard.pbix` in Power BI Desktop to explore the data model, DAX measures, and interactive visuals.
3. Refer to `Task_4_Star_Schema_Model.png` for the relationship diagram between fact and dimension tables.
4. Refer to `Business_Insights_Report_Task4.pdf` for the full analysis and recommendations.

---

## ⚠️ Data Notes

- Profit is calculated as Sales Amount less Total Product Cost at the order-line level.
- The dataset's `Unit Price Discount Pct` field is present but populated at 0% across every order line, so no discount-impact analysis is included in this report (unlike Tasks 2 and 3, where discounting was a material factor).
- FY2020 data runs through 15 June 2020, just short of fiscal year-end, and is treated as effectively complete.

---

## 👤 Author

**Prince Kumar**
MBA (Business Analytics), Delhi School of Management, DTU
Data Analytics & BI Intern, Maincrafts Technology

---

## 🙏 Acknowledgment

Thanks to **Maincrafts Technology** for the opportunity and structured task guidelines that shaped this project.
