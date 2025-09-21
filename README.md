# Cloud-Cost-Dashboard
End-to-end Power BI project simulating enterprise cloud costs by billing data and delivering KPIs, cost trends, and actionable insights

📌 Purpose

This dashboard was developed to simulate a realistic cloud cost monitoring tool, showcasing cost breakdowns across services, regions, and time periods.
Note: All data used is synthetically generated to replicate real-world scenarios based on my prior work experience. The guide for the synthetically generated data can be looked in this repo (https://github.com/TejaGaneshBalaji/synthetic-datasets).

🛠 Tech Stack

📊 Power BI Desktop – for dashboard creation and interactivity
📂 Power Query – for ETL, cleaning, and reshaping data
🧮 DAX – for calculated measures, KPIs, and dynamic visuals
📝 Data Modeling – establishing relationships between service, cost, and region tables
📁 File Format – .pbix (development) & .png (preview screenshots)

📂 Data Source & Cost Breakdown

The data models synthetic cloud billing tables, built to represent how organizations typically track cloud costs.

🗄 Database Simulation:
Service Table – Cloud services (Compute, Storage, Database, Networking, etc.)
Databases Table – DB costs (InfluxDB(Avien), MongoDB, OracleDB, etc.)
Usage Table – Resource consumption in units (e.g., GB, vCPU hours)
Cost Table – Final cost per month data after applying rates

## 📂 Data Source

Synthetic dataset created to model multi-cloud cost behavior.
Covers services, regions, time-series costs, and usage categories to mimic enterprise reporting needs.

## ⭐ Features & Highlights

Business Problem:
Cloud costs are complex and fragmented, making it difficult for finance and engineering teams to track spending trends and identify optimization opportunities.

* **Goal**
  To provide a **centralized dashboard** that delivers:

  * Cost transparency across PROD,DEV,TESTING & services
  * Trend analysis of spend over time
  * KPI tracking for budget vs. actuals
  * Drill-downs for optimization insights

* **Walkthrough of Key Visuals**

  * **Top KPIs (Header):** Total spend, budget variance, top service, and top groups
  * **Trend Analysis (Line Chart):** Monthly/yearly cost progression
  * **Service Breakdown (Bar Chart):** Costs split by cloud, Database services
  * **Optimization Panel:** Highlighting top cost drivers and savings potential

* **Business Impact & Insights**

  * Enables finance teams to track budget compliance
  * Helps engineering teams identify cost-intensive services
  * Supports management decisions on resource allocation and cloud strategy

## 📸 Screenshots / Demo

Here’s what the dashboard looks like:  

![Dashboard Overview](https://github.com/TejaGaneshBalaji/Cloud-Cost-Dashboard/blob/main/1_%20Overview%20of%20Cloud%20Costs.png)


![Cost Trends](https://github.com/TejaGaneshBalaji/Cloud-Cost-Dashboard/blob/main/2_%20Detailed%20cost%20of%20Infrastructure%20and%20Operational.png)

![Alt Text](https://github.com/TejaGaneshBalaji/Cloud-Cost-Dashboard/blob/main/3_%20Cloud%20Services%20costs%20in%20detail.png)
