# 📦 Warehouse Performance Analysis (SQL + Excel Dashboard)

## 🏗️ Project Overview
This project focuses on **Warehouse Performance Analysis** using **SQL** for data analysis and **Excel Dashboard** for visualization.  
It helps in tracking and improving warehouse operations through key KPIs like **cost efficiency, manpower optimization, space utilization, and inventory turnover**.

---

## 🎯 Objectives
- Analyze warehouse data to identify cost-saving opportunities 💰  
- Optimize space and manpower utilization 🧭  
- Monitor wrong issuance, claims, and overtime trends ⚙️  
- Build a visually interactive Excel dashboard for management insights 📊  

---

## 🧮 Data Source
The dataset is structured across multiple sheets (Lease Cost, Space Utilization, Inventory, Claims, Overtime, etc.) containing monthly operational data extracted from warehouse systems.

| Sheet Name | Description |
|-------------|-------------|
| Lease Cost | Monthly lease cost allocated vs used |
| Space Utilization | Space allocated vs space used |
| Inventory Turnover Ratio | COGS and Average Inventory data |
| Reduce Overtime | Monthly overtime percentage |
| Reduce Claims | Claim costs per month |
| Reduce Wrong Issuance | Outbound vs Wrong Issuance quantity |
| Contractual KPIs | SCL Efficiency, Baseline, Charges, and Savings |

---

## 🧠 SQL Analysis Requirements

### 🔹 Basic Analysis
- These help you practice SELECT, WHERE, ORDER BY, and simple aggregates.
1.	Show all warehouses and their total inbound and outbound shipment counts. (Inbond & Outbond.csv)
2.	List all warehouse locations with their space utilization percentage. (Space Utilization.csv)
3.	Find the average overtime hours across all warehouses. (Reduce Overtime.csv)
4.	Display the inventory turnover ratio for each month. (Inventory Turnover Ratio.csv)
5.	List warehouses that have lease cost above average. (Lease Cost.csv)

### 🔹 Intermediate Analysis
- These connect performance, cost, and space data.
1.	Join Warehouse Performance.csv and Reduce Overtime.csv to find if higher overtime correlates with lower performance.
→ Hint: JOIN on warehouse ID or name.
2.	Combine Lease Cost.csv and Space Utilization.csv to find the cost per utilized square meter of space.
3.	Use Inbond & Outbond.csv and Reduce Wrong Issuance.csv to find the error rate per total dispatch.
4.	Join Reduce Claims.csv and Contractual Kpis.csv to compare actual claims with KPI targets.
5.	Combine Inventory Turnover Ratio.csv with Warehouse Performance.csv to check how turnover affects warehouse score.

### 🔹 Advanced Analysis
- These simulate real business analysis using multiple tables.
1.	Build a query joining Warehouse Performance, Reduce Claims, and Reduce Wrong Issuance to find which warehouses have highest overall efficiency (least errors + highest performance).
2.	Join Lease Cost, Space Utilization, and Warehouse Performance to find top 3 warehouses with the best performance-to-cost ratio.
3.	Combine all related datasets (Inbond & Outbond, Reduce Overtime, Reduce Claims, Inventory Turnover Ratio) to create a monthly performance summary report for each warehouse.
4.	Use subqueries to find warehouses where the inventory turnover is above average and lease cost is below average.
5.	Create a KPI compliance report by joining Contractual Kpis, Warehouse Performance, and Reduce Overtime to check which warehouses meet or exceed contractual performance targets.

---

## 📊 Excel Dashboard Overview

### 🧭 KPIs Displayed
| KPI | Description |
|------|-------------|
| Total Savings ($) | Measures monthly and total savings |
| SCL Efficiency (%) | Shows logistics cost efficiency |
| Space Utilization (%) | Tracks warehouse space usage |
| Inventory Turnover Ratio | Indicates inventory movement speed |
| Wrong Issuance Reduction | Tracks outbound accuracy |
| Claim Reduction ($) | Shows claims and loss trend |
| Overtime % | Measures extra working cost |
| Manpower Optimization | Compares manpower cost vs outbound |

---

### 📈 Charts & Visuals
1. **Lease Cost vs Savings** – Clustered bar chart comparing allocated vs used cost  
2. **SCL Efficiency Trend** – Line + bar combo for quarterly performance  
3. **Space Utilization** – Bar chart showing used vs allocated area  
4. **Wrong Issuance Analysis** – Outbound vs wrong issuance quantity  
5. **Claims Trend** – Column chart for monthly claim amount  
6. **Overtime %** – Bar chart for manpower cost tracking  
7. **Inventory Turnover Ratio** – Dual-axis chart for COGS vs Inventory  
8. **KPI Cards** – Highlights of total savings, baseline, and efficiency  

---

## 🧩 Tools & Technologies
- **SQL** – Data extraction, cleaning & KPI calculations  
- **Excel (Power Query, Charts, Pivot Tables)** – Data visualization & dashboard design  
- **Power BI (Optional)** – For advanced interactivity  
- **MS Excel Macros (.xlsm)** – For automated dashboard refresh  

---

## 💡 Key Insights
- Achieved **26.98% actual savings** versus target  
- **SCL Efficiency improved** consistently over months  
- **Wrong issuance reduced drastically** in Q4  
- **Overtime cost** peaked in March – requires manpower optimization  
- **Space Utilization** maintained above 90% efficiency  

---

## 🚀 Future Enhancements
- Automate SQL data import to Power BI  
- Add forecasting for cost and efficiency trends  
- Integrate real-time warehouse IoT sensor data  

---

## 👨‍💻 Author
**Ankush Kumar**  
📍 Data Analytics & Dashboard Enthusiast  
📫 [LinkedIn](https://www.linkedin.com/in/ankush-kumar-05511236a/)

---

## 🏷️ Tags
`#SQL` `#ExcelDashboard` `#WarehouseAnalytics` `#DataVisualization` `#Operations` `#KPI` `#DataAnalysis`

