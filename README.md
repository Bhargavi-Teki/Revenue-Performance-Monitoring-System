# 💰 Revenue Performance Monitoring System (RPMS)

## 📌 Overview
The Revenue Performance Monitoring System (RPMS) is an interactive Power BI dashboard designed to analyze global retail sales performance across regions, product categories, and store tiers.

The objective of this project is to transform multi-year transactional data into actionable business insights that support revenue optimization and operational benchmarking.

---

## 🎯 Business Objectives

- Analyze the 25.8% Year-over-Year revenue shift (2019–2020)
- Evaluate product concentration risk (Smartphones contributing 60%+ of total revenue)
- Benchmark Rank A1 (Store 1) performance against lower-tier outlets
- Identify seasonal revenue volatility and regional market distribution

---

## 🛠 Tech Stack

- **Power BI** – Data modeling & interactive dashboard development  
- **Power Query (ETL)** – Data cleaning, transformation & automated workflows  
- **DAX** – Custom KPI engineering and analytical measures  

---

## 📊 Core KPIs

```DAX
Total Revenue = SUM(Sheet1[Revenue (USD)])
Avg Revenue = AVERAGE(Sheet1[Revenue (USD)])
Total Transactions = COUNT(Sheet1[First Name])
Total Countries = DISTINCTCOUNT(Sheet1[Country])
```

Additional performance indicators include Revenue by Store Rank, Product Category and Region.

---

## 📂 Data Source

The analysis is based on the **Global Retail Operations Dataset** (sourced from an open-source commercial repository). It features comprehensive multi-market records across Asia, the UK, and the USA, providing a robust framework for international sales analysis.

---

## 📈 Key Visualizations

- **Treemap** – Revenue distribution across store ranking tiers
- **Donut Chart** – Product category contribution to total revenue
- **Ribbon Chart** – Product ranking shifts over time
- **Combo Chart** – Revenue trends vs transaction volume comparison
- **Pie Chart** – Regional market share breakdown
- **Infographic Panels** – Sales representative performance & gender-based demographic insights

--- 

## 💡 Strategic Insights

1.Smartphone Dominance: Generated ~$78.9M (60%+ of total revenue), indicating strong market fit but high portfolio dependency.
2.Operational Benchmark: Rank A1 (Store 1) locations contribute nearly 50% of global revenue, establishing a clear model for upskilling lower-tier outlets.
3.Seasonality: Significant Q1 contraction observed between 2019–2020, highlighting a need for more resilient early-year marketing strategies.
4.Diversification: Accessories and Tablet segments present clear opportunities to reduce product concentration risk.
5.Market Expansion: Revenue distribution indicates regional dominance in specific markets, suggesting high-potential zones for targeted expansion.

---

## 🧠 What I Learned

* Building end-to-end BI dashboards
* Writing optimized DAX measures
* Structuring automated ETL workflows in Power Query
* Designing executive-level visual narratives

---

## 📊 Dashboard Preview

![RPMS Dashboard](https://github.com/Bhargavi-Teki/Revenue-Performance-Monitoring-System/blob/main/RPMS_Executive_Overview.png.png)

