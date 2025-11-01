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
- Retrieve total lease cost allocated and used per month  
- Calculate total claims and overtime %  
- Find all unique months and warehouse IDs  

### 🔹 Intermediate Analysis
- Calculate savings (Lease Cost Allocated – Lease Cost Used)  
- Compute space utilization efficiency `(Space_Used / Space_Allocated) * 100`  
- Join inbound and outbound data for monthly comparison  
- Rank months by highest savings  

### 🔹 Advanced Analysis
- Use CTEs to calculate cumulative savings  
- Apply window functions for month-over-month trends  
- Create performance categories using `CASE WHEN`  
- Build a combined KPI summary using joins and aggregation  

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

