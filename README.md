<!-- HEADER -->
<div align="center">

# 🛒 E-Commerce Profitability & Operational Efficiency Audit

### A structured business intelligence analysis of an e-commerce platform
### answering 26 business questions across products, revenue, customers, channels, returns, and seasonality

<br/>

![Python](https://img.shields.io/badge/Tools-Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

<br/>

> **Analyst:** Ubaid — Final-Year BS Chemistry Student, Islamia University of Bahawalpur  
> **Skills demonstrated:** Data Analysis · Business Intelligence · Excel Dashboarding · Statistical Thinking  
> **Dataset:** [Olivedd E-Commerce Sales & Customer Analytics — Kaggle](https://www.kaggle.com/datasets/datascikhan/e-commerce-sales-and-customer-analytics)

</div>

---

## 📌 Project Overview

This project performs a **full profitability and operational efficiency audit** of a simulated e-commerce platform using a publicly available Kaggle dataset. It mirrors the kind of analysis a junior data or business analyst would be asked to produce for a Chief Operating Officer (CO) or Chief Financial Officer (CFO).

The analysis spans **60 months** of transaction data and covers:

- **138,116 orders** across 4 customer segments
- **5 regional markets** and **10 acquisition channels**
- Discount sensitivity, return behaviour, delivery performance, and seasonal demand patterns
- **26 structured business questions** with data-backed answers

---

## 📂 Repository Structure

```
E-Commerce-Profitability-Operational-Efficiency-Audit/
│
├── 📊 olivedd_dashboard.xlsx        # 10-sheet dark-theme Excel BI dashboard (13 charts)
├── 📄 olivedd_bi_report.docx        # Word report: 26 Q&A answers with key findings
├── 📁 data/
│   └── analysed_results.xlsx        # Pre-processed summary results used in this analysis
├── 📓 analysis_notebook.ipynb       # (optional) Python EDA notebook
└── 📝 README.md                     # This file
```

---

## 🧩 Business Questions Answered

<details>
<summary><b>📦 Products & Categories (Q1–Q4, Q10, Q17)</b></summary>

| # | Question |
|---|---|
| Q1 | Which products generate the highest revenue? |
| Q2 | Which products generate the highest profit? |
| Q3 | Which categories contribute most to total sales? |
| Q4 | Which brands perform best? |
| Q10 | Which products have high sales but weak margins? |
| Q17 | Which products demonstrate strong demand? |
| Q26 | Which is the most-selling product? |

</details>

<details>
<summary><b>💰 Revenue, Profit & Discounts (Q6, Q7, Q20)</b></summary>

| # | Question |
|---|---|
| Q6 | How does discounting affect revenue? |
| Q7 | How does discounting affect profitability? |
| Q20 | Which categories combine strong sales and profitability? |

</details>

<details>
<summary><b>🛒 Customers & Segments (Q5, Q15, Q16, Q22, Q24)</b></summary>

| # | Question |
|---|---|
| Q5 | Which customers generate the greatest business value? |
| Q15 | How does loyalty relate to purchasing behaviour? |
| Q16 | Which customer segments are most valuable? |
| Q22 | Does discount sensitivity differ between customer groups? |
| Q24 | Can customer behaviour be used to create meaningful segments? |

</details>

<details>
<summary><b>📢 Channels & Regions (Q8, Q9, Q21, Q23)</b></summary>

| # | Question |
|---|---|
| Q8 | Which acquisition channels perform best? |
| Q9 | Which regions generate the highest sales? |
| Q21 | Which acquisition channels attract high-value customers? |
| Q23 | Does purchasing behaviour differ by region? |

</details>

<details>
<summary><b>↩️ Returns & Delivery (Q11–Q14)</b></summary>

| # | Question |
|---|---|
| Q11 | Which products experience higher return activity? |
| Q12 | What are the most common return reasons? |
| Q13 | Does delivery time relate to customer ratings? |
| Q14 | Does delivery performance relate to returns? |

</details>

<details>
<summary><b>📅 Trends & Hidden Patterns (Q18, Q19, Q25)</b></summary>

| # | Question |
|---|---|
| Q18 | What seasonal patterns exist? |
| Q19 | How does customer behaviour change over time? |
| Q25 | What hidden relationships exist between customers, products, sales, and operations? |

</details>

---

## 📊 Excel Dashboard — 10 Sheets, 13 Charts

The dashboard was built in **dark professional theme** (designed for executive presentation).

| Sheet | Contents |
|---|---|
| 🏠 **Dashboard** | 8 KPI cards · Discount tier summary · Segment overview · 2 charts |
| 📦 **Products** | Top products · Category revenue index · Brand table · 1 chart |
| 💰 **Revenue\_Profit** | Discount deep dive · Net rev vs profit chart · Margin decline line |
| 🛒 **Customers** | Top 10 customer table · Segment behaviour analysis · 2 charts |
| 📢 **Channels\_Regions** | Channel × region matrix · Regional summary · 2 charts |
| 💸 **Discounts** | Segment discount analysis · 5 strategic insights · Line chart |
| ↩️ **Returns** | 8 return reasons + action items · Pie chart · Delivery vs rating chart |
| 📅 **Seasonality** | 60-month data · Revenue trend line · Order volume line |
| 📋 **Data\_Tables** | Full filterable master table · AutoFilter enabled · Pivot/Slicer ready |
| ℹ️ **Notes** | Metadata · 7 key findings · Data source · Analyst info |

> **How to add Slicers:** Go to `Data_Tables` sheet → click any cell in the table → `Insert → Table` → `Insert → Slicer` → select Channel, Region, or Segment.

---

## 🔑 Key Strategic Findings

> These are the top findings a CO or CFO would act on immediately.

| # | Finding | Impact |
|---|---|---|
| 🔴 1 | **Heavy discounts (>20%) reduce profit margin by 21.5pp** — from 54.11% to 32.58% | $15.8M lost to discounts per period |
| 🔴 2 | **Late delivery triggers 22.83% return rate** vs 0% for on-time delivery | Every 1,000 late orders → ~228 returns |
| 🔴 3 | **Premium & VIP customers are over-subsidised** — 20%+ discount, same return rate as Consumers | Policy restructuring needed |
| 💡 4 | **North region is underinvested** — highest CLV ($9,300–$9,500) and margin (48–49%) | Growth opportunity with low acquisition cost |
| 💡 5 | **Revenue peaks every Nov–Dec** — 50–80% above monthly baseline, consistent across all 5 years | Plan inventory and logistics 8 weeks ahead |
| 💡 6 | **Organic Search drives ~18.5% of total platform revenue** — single largest channel | Protect SEO investment; do not cut |
| 💡 7 | **All top 10 profit customers are 'Loyal' type** — loyalty programme = highest LTV multiplier | Scale loyalty programme acquisition |

---

## 🏆 Top Results at a Glance

| Metric | Result |
|---|---|
| Most-Sold Product | PROD-000839 — Arm & Hammer (Grooming) |
| Top Revenue Product | PROD-000024 — Asus Tablet (Electronics) |
| Top Profit Customer | James Long — $13,994 profit |
| Top Revenue Customer | Dylan Clark — $30,268 net sales, 15 orders |
| Best Brand | Puma (Sales) · Williams-Sonoma (Value) |
| Best Channel | Organic Search ($35.66M) · YouTube North (49.12% margin) |
| Best Region by Revenue | South ($44.07M) |
| Best Region by Margin | North (48.17%) |
| Best Discount Tier | No Discount — 54.11% margin |
| Highest Return Reason | Wrong Product (15.6%) |

---

## 🛠️ Tools & Skills Used

| Tool / Skill | Application |
|---|---|
| **Microsoft Excel** | Dashboard design, chart creation, AutoFilter, conditional formatting |
| **Python (pandas, openpyxl)** | Automated .xlsx generation, data structuring |
| **Statistical Analysis** | Margin analysis, CLV comparison, discount sensitivity, return rate correlation |
| **Business Intelligence** | KPI framing, executive summary writing, segment profiling |
| **Data Storytelling** | Translating raw numbers into actionable CO/CFO-level insights |

---

## 📄 Word Report

The accompanying `olivedd_bi_report.docx` contains:

- **Executive Summary** — 6 top-level strategic findings
- **26 business questions answered** — each with a 4–5 line analytical paragraph
- **4 bullet key findings per question** — directly actionable recommendations
- **Appendix** — dashboard guide, slicer instructions, data source

---

## 📁 Dataset

**Source:** [Kaggle — datascikhan/e-commerce-sales-and-customer-analytics](https://www.kaggle.com/datasets/datascikhan/e-commerce-sales-and-customer-analytics)  
**Coverage:** 60 months · 138,116 orders · 4 segments · 5 regions · 10 channels  
**Note:** This is a synthetic/simulation dataset used for educational and portfolio purposes.

---

## 👤 About the Analyst

**Ubaid** — Final-year BS Chemistry student at **Islamia University of Bahawalpur, Pakistan** (CGPA: 3.84/4.0).  
Combining an analytical chemistry background with data analysis skills (Excel, Python, SQL, Power BI) to build a cross-disciplinary portfolio spanning chemometrics, business intelligence, and open science.

[![GitHub](https://img.shields.io/badge/GitHub-ur--chemist-181717?style=flat-square&logo=github)](https://github.com/ur-chemist)
[![Kaggle](https://img.shields.io/badge/Kaggle-Profile-20BEFF?style=flat-square&logo=kaggle)](https://www.kaggle.com)
[![Zenodo](https://img.shields.io/badge/Zenodo-DOI%3A10.5281%2Fzenodo.21911163-blue?style=flat-square)](https://doi.org/10.5281/zenodo.21911163)

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.  
Dataset credit: Kaggle user **datascikhan**.

---

<div align="center">

*Built as part of a Data Analytics Portfolio — demonstrating analytical thinking, BI dashboard design, and business communication skills.*

</div>
