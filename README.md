# 📊 E-Commerce Profitability & Operational Efficiency Audit

## 🏢 Executive Summary
This project analyzes a comprehensive e-commerce dataset (100,000+ transactions) to identify drivers of margin erosion and customer churn. The analysis reveals that aggressive discounting for "VIP" segments is actively destroying profitability, while logistical delays are the primary catalyst for product returns. Strategic reallocation of marketing spend and operational fixes are recommended to recover an estimated 15-20% in net margins.

## 🎯 Business Problem
Despite high order volumes, the company faces declining net profitability. Leadership needs to understand:
1. Is the current discount strategy driving sustainable revenue, or merely subsidizing low-margin sales?
2. Which acquisition channels and regions deliver the highest Customer Lifetime Value (CLV)?
3. What operational factors are driving the high rate of product returns?

## 💡 Key Analytical Findings
* **The "Discount Trap":** Orders with **no discount** yield the highest profit margin (54.11%). Conversely, heavy discounts (>20%) collapse margins to 32.58%. VIP and Premium segments, while generating high order volume, consume 20%+ in discounts, making them less profitable than the standard "Consumer" segment.
* **Logistics-Driven Churn:** Delivery performance is the strongest predictor of returns. **Late deliveries** result in a **22.83% return rate** and drop average customer ratings to 3.22/5.0, compared to a 0% return rate and 3.75/5.0 rating for on-time deliveries.
* **High-Value Acquisition:** While the "South" region drives the highest volume, the "North" region yields the highest profitability. Specifically, **YouTube** (49.12% margin) and **Direct** (48.53% margin) channels in the North outperform high-volume channels like Organic Search (44.06% margin).

## 🛠️ Technical Implementation
* **Data Extraction & Transformation:** Advanced SQL (CTEs, Window Functions, Date Math) to aggregate multi-table relational data into business-ready metrics.
* **Exploratory Data Analysis (EDA):** Python (Pandas, Seaborn) to visualize margin erosion, cohort behavior, and operational bottlenecks.
* **Business Intelligence:** Translated raw statistical outputs into actionable strategic recommendations for Marketing and Operations teams.

## 📂 Repository Contents
* `sql/business_analysis.sql`: Production-ready SQL queries for CLV, margin, and retention analysis.
* `python/visualizations.py`: Clean, annotated Python scripts generating executive-level charts.
* `insights/recommendations.md`: Detailed strategic action plan based on the data.

## 🚀 Tech Stack
`PostgreSQL` | `Python` | `Pandas` | `Data Storytelling` | `Business Intelligence`
