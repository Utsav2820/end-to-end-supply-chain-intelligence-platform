# 📦 End-to-End Supply Chain Intelligence Platform

> An interactive **Power BI Business Intelligence solution** designed to analyze and optimize supply chain operations through delivery performance, inventory risk monitoring, financial insights, and operational analytics.

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Analytics-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)
![Data Modeling](https://img.shields.io/badge/Star%20Schema-Data%20Model-orange)

---

## 📖 Project Overview

Supply chains generate massive volumes of operational data every day. Without proper analytics, identifying delays, inventory shortages, supplier issues, and revenue opportunities becomes difficult.

This project transforms raw supply chain data into an interactive Power BI dashboard that enables stakeholders to monitor KPIs, identify operational bottlenecks, and make data-driven decisions.

---

## 🎯 Business Objectives

- Monitor end-to-end supply chain performance
- Track delivery delays and their root causes
- Analyze revenue and profitability across regions
- Identify inventory at risk below safety stock
- Evaluate supplier and warehouse performance
- Provide executive-level operational insights

---

## 📊 Dashboard Pages

### 🏠 Home Dashboard
- Overall supply chain KPI overview
- Performance snapshot
- Revenue by category
- Quarterly order trends
- Dynamic business insights

### 📈 Executive Overview
- Revenue & Profit Analysis
- Category Performance
- Regional Comparison
- Delay Reason Analysis
- Supplier Damage Analysis

### 🚚 Delivery Performance
- On-Time Delivery %
- Delivery Partner Performance
- Weather Impact Analysis
- Delay Reasons
- Expected vs Actual Delivery Time

### 📦 Inventory Risk
- Inventory Health Monitoring
- Safety Stock Analysis
- Warehouse Comparison
- Inventory Buffer
- At-Risk Product Categories

### 📋 Order Details
- Complete order-level analysis
- Revenue & Profit Tracking
- Delivery Status
- Customer Segments
- Interactive filtering

---

## 📌 Key KPIs

| KPI | Description |
|------|-------------|
| Total Orders | Total processed customer orders |
| Total Revenue | Revenue generated from all orders |
| Net Profit | Overall business profitability |
| Delayed Orders | Number of delayed deliveries |
| On-Time Delivery % | Orders delivered within expected time |
| Avg Delivery Time | Average delivery duration |
| Avg Delivery Rating | Customer satisfaction rating |
| Damage % | Percentage of damaged shipments |
| Inventory Risk % | Inventory below safety stock |
| Inventory Buffer | Available inventory above safety stock |

---

## 🛠 Tech Stack

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Star Schema Data Modeling**
- **Microsoft Excel** (Data Preparation)

---

## 🗂 Data Model

The report follows a **Star Schema** architecture for optimized analytical performance.

**Fact Table**
- Fact_Orders

**Dimension Tables**
- Dim_Product
- Dim_Customer
- Dim_Supplier
- Dim_Warehouse
- Dim_Partner

---

## ⚡ DAX Highlights

Some of the key measures developed include:

- Total Revenue
- Net Profit
- Total Orders
- Delayed Orders
- On-Time Delivery %
- Damage %
- Inventory Risk %
- Inventory Buffer
- Avg Delivery Time
- Avg Delivery Rating
- Dynamic Business Insight Measures
- Top Revenue Category
- Top Revenue Region

Advanced DAX functions used:

`CALCULATE` • `DIVIDE` • `AVERAGEX` • `TOPN` • `SUMMARIZE` • `VAR` • `MAXX` • `FORMAT`

---

## 💡 Key Business Insights

- Electronics contribute the highest overall revenue.
- More than **80%** of orders experienced delivery delays.
- Customs clearance is the leading cause of delayed deliveries.
- Nearly **15%** of inventory is below the defined safety stock level.
- Supplier damage rates vary significantly and require continuous monitoring.
- Weather conditions have a noticeable impact on delivery performance.

---

## 🧹 Data Preparation

The dataset was sourced from **Kaggle** and prepared using **Power Query**.

Data preprocessing included:
- Removing duplicate records
- Correcting data types
- Handling inconsistent values
- Creating relationships
- Building a Star Schema data model

---


## 📂 Repository Structure

```
end-to-end-supply-chain-intelligence-platform/
│
├── assets/
│   ├── home_dashboard.png
│   ├── executive_overview.png
│   ├── delivery_performance.png
│   ├── inventory_risk.png
│   └── order_details.png
│
├── reports/
│   └── SupplyChain_Intelligence.pbix
│
└── README.md
```

---

## 🚀 Getting Started

1. Clone this repository

```bash
git clone https://github.com/Utsav_2820/end-to-end-supply-chain-intelligence-platform.git
```

2. Open **SupplyChain_Intelligence.pbix** using **Power BI Desktop**.

3. Explore the interactive dashboards using the navigation menu and slicers.

---

## 🎓 Skills Demonstrated

- Business Intelligence
- Supply Chain Analytics
- Logistics Performance Analysis
- Inventory Risk Assessment
- KPI Development
- DAX Programming
- Power Query ETL
- Data Modeling
- Dashboard Design
- Data Storytelling

---

## 👨‍💻 Author

**Utsav Sharma**

GitHub: [@Utsav_2820](https://github.com/Utsav2820)

