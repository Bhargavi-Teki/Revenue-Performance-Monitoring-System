# 💰 Revenue Performance Monitoring System (RPMS)

### 📌 Project Overview
The **Revenue Performance Monitoring System (RPMS)** is a business intelligence solution developed to track and analyze global sales dynamics. By synthesizing multi-year transactional data, this system provides a high-level view of regional performance, product health, and sales force efficiency, enabling data-driven decision-making for commercial growth.

---

### 🛠 Tech Stack & Process
* **Power BI:** End-to-end data modeling and interactive dashboard design.
* **Power Query (ETL):** All data cleaning, attribute profiling, and structural transformations were performed directly within Power BI to ensure an automated data pipeline.
* **Used DAX:** Engineered custom measures to drive core KPIs and analytical depth:
  * `Total Revenue = SUM(Sheet1[Revenue (USD)])`
  * `Avg Revenue = AVERAGE(Sheet1[Revenue (USD)])`
  * `Total Transactions = COUNT(Sheet1[First Name])`
  * `Total Countries = DISTINCTCOUNT(Sheet1[Country])`

---

### 📂 Data Source
The analysis is based on the **Global Retail Operations Dataset** (sourced from an open-source commercial repository). It features comprehensive multi-market records across Asia, the UK, and the USA, providing a robust framework for international sales analysis.

---

### 🎯 Business Problem
The project was engineered to solve three critical commercial challenges:
1. **Revenue Volatility:** Analyzing the root causes behind the 25.8% year-over-year revenue shift between 2019 and 2020.
2. **Product Portfolio Risk:** Evaluating the high dependency on the Smartphone category and identifying growth levers.
3. **Operational Benchmarking:** Mapping the performance gap between "Store 1" (High-Rank) and lower-ranked outlets.

---

### 🏆 Goals
* **Trend Identification:** Isolate seasonal peaks and troughs to optimize inventory and marketing spend.
* **Operational Standardization:** Benchmark top-tier store performance to create a roadmap for upskilling underperforming regions.

---

### 📊 Key Visuals

- **Interactive Treemap** – Analyzed revenue weight across Store Level Ranks to identify primary revenue-driving tiers.
- **Custom Infographics** – Streamlined Sales Representative performance and Gender-based demographic insights for quick-glance analysis.
- **Donut & Ribbon Charts** – Illustrated product category composition and tracked ranking shifts between product lines over time.
- **Combo Charts** – Integrated multiple data dimensions to compare Revenue trends against Transaction volumes on a single axis.
- **Pie Chart(Regional Market Share)** – Mapped total revenue by Country and Region to highlight market dominance and growth areas.

---

### 💡 Strategic Insights & Observations
* **The Revenue Anchor:** Smartphones drive over 60% of total revenue ($78.9M). While a major strength, this indicates a clear opportunity to increase market penetration in the Accessories and Tablet segments.
* **Top-Tier Dominance:** Data confirms that **Store 1 (Rank A1)** locations drive nearly 50% of global revenue. This serves as the "Gold Standard" blueprint for upskilling underperforming store tiers.
* **Seasonal Sensitivity:** A sharp contraction in Q1 performance from 2019 to 2020 indicates that the business is highly sensitive to early-year market shifts, requiring more resilient Q1 promotional strategies.

---

### 🧠 Key Learnings
* **Data Storytelling:** Learned to create a "Monitoring System" that guides users through a business narrative.
* **DAX Implementation:** Gained proficiency in writing measures to calculate business KPIs across large datasets.
* **UX/UI Design:** Mastered using infographics and treemaps to make complex hierarchical data easy to interpret.
* **Automated ETL:** Improved proficiency in using Power Query to clean and structure data directly within Power BI.

---

### 🖥️ Screenshot
Below is a snapshot of the **RPMS** dashboard, designed for clarity and executive-level navigation:

![Revenue Performance Monitoring System Dashboard](https://github.com/Bhargavi-Teki/Revenue-Performance-Monitoring-System/blob/main/RPMS_Executive_Overview.png.png))]
