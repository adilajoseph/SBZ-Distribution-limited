# SBZ-Distribution-limited
Investigated delivery time in logistics operations with the KPIs. Analyzed root causes using Power BI, delivering interactive dashboards for executive insight.

## 📘 Project Overview

This Power BI project was developed to support the **Logistics Planning and Analysis** team in tracking, analyzing, and optimizing key logistics metrics. The dashboard provides a centralized, interactive view of KPIs including **spend**, **utilization**, and **performance against goals** — enabling stakeholders to make informed decisions that improve operational efficiency, cost-effectiveness, and sustainability across logistics functions.

---

## 🧰 Tools & Technologies

- **Power BI Desktop**
- **Power Query** for ETL (Extract, Transform, Load)
- **DAX** (Data Analysis Expressions) for calculated fields and KPIs
- **SQL/Excel** (optional) for source data handling
- **Power BI Service** for sharing and collaboration

---

## 🎯 Project Objectives

- Track and visualize **Logistics KPIs** to support operational and strategic decisions
- Provide insights into **spend trends**, **carrier utilization**, and **goal performance**
- Enable **continuous improvement** through data-driven analysis
- Identify **sustainability opportunities** and **efficiency gaps**

---

## 🧾 Key Metrics & Calculations

| KPI / Measure              | Description                                                   | Sample Formula (DAX)                                      |
|----------------------------|---------------------------------------------------------------|-----------------------------------------------------------|
| `Total Spend`              | Total logistics-related spend                                  | `SUM(Spend)`                                              |
| `Utilization Rate (%)`     | Capacity or asset usage rate                                   | `DIVIDE(Used_Capacity, Available_Capacity) * 100`         |
| `On-Time Delivery (%)`     | % of shipments delivered on or before the expected date        | `DIVIDE(OnTimeShipments, TotalShipments) * 100`           |
| `Cost per Shipment`        | Average cost incurred per shipment                             | `DIVIDE(Spend, TotalShipments)`                           |
| `Performance vs Target`    | Variance between actual KPIs and set goals                     | `Actual KPI - Target KPI`                                 |
| `Sustainability Score`     | Emissions or waste metrics (optional)                          | Custom calculation based on available sustainability data |

---

## 📊 Dashboard Sections

### 1. 🧮 **KPI Summary**
- Cards displaying Total Spend, Utilization Rate, On-Time Delivery %, Cost/Shipment, Performance vs Goal

### 2. 📈 **Spend Trend Analysis**
- Line chart showing spend over time (weekly/monthly)
- Optional: Breakdown by carrier, route, or business unit

### 3. 🚚 **Utilization Dashboard**
- Clustered bar or stacked chart for used vs available capacity
- Drill-through to region, carrier, or asset type

### 4. 🎯 **Performance vs Goals**
- Bullet chart or gauge to compare actual metrics with targets
- Highlights areas exceeding or falling short of goals

### 5. 🗺️ **Geographic Insights**
- Map visualization showing delivery routes or performance by region

### 6. 🌿 **Sustainability Metrics** (Optional)
- CO₂ emissions, green mile % or other sustainability indicators

### 7. 🔎 **Interactive Slicers**
- Time Period (Date Range)
- Region
- Carrier
- Shipment Type
- KPI Target Range

---

## 💼 Business Impact

| Business Area           | Benefit                                                              |
|--------------------------|----------------------------------------------------------------------|
| Logistics Operations     | Improved visibility into delivery and cost performance               |
| Financial Planning       | Better control over logistics spend and cost per shipment            |
| Sustainability           | Supports tracking of emissions and green logistics initiatives       |
| Continuous Improvement   | Enables root cause analysis and operational refinement               |
| Executive Reporting      | Instant access to strategic metrics with drill-down capabilities     |
