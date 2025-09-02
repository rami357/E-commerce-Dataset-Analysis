# 📊 Sales Performance Dashboard - Power BI

This project showcases an **interactive Power BI dashboard** built to analyze **sales performance, shipments, products, and profitability** using a structured dataset. The dashboard provides insights into business performance across geographies, products, and sales teams.

---

## 🚀 Project Overview
The dashboard was created to:
- Track **total sales, profit, and shipment performance** over time.
- Compare **current year (CY) vs previous year (PY)** trends.
- Analyze **regional sales contribution**.
- Identify **top-performing salespersons** and **products**.
- Provide distribution analysis of shipments.

---

## 📂 Dataset
The project uses a **relational data model** with multiple tables connected via primary and foreign keys.

### Data Model
- **locations**: Contains geographical details (Geo, GID, Region).  
- **products**: Product details (Product, Category, Cost per box, PID).  
- **calendar**: Time dimension for reporting (date, month, weekday, etc.).  
- **people**: Salesperson details (Sales_person, Team, Picture, SPID).  
- **shipments**: Transaction fact table (Amount, Boxes, Cost, GID, PID, Order_Status).

---

## 📊 Dashboard Features
### KPIs
- **Total Sales**: $141.5M  
- **Total Boxes Shipped**: 8.8M  
- **Shipment Count**: 25K  
- **Profit**: $81.1M  
- **Profit %**: 57.3%  

### Visuals
1. **Sales & Boxes Trend (CY vs PY)** – Year-over-year performance.  
2. **Shipment Distribution Histogram** – Frequency of shipment sizes.  
3. **Top 6 Products** – Highest revenue-generating products.  
4. **Top 6 Salespersons** – Ranked by total sales & profit %.  
5. **Regional Sales Distribution (Donut Chart)** – Contribution by country.  
6. **Product Profitability Table** – Product-level sales, profit, and margin %.  

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Data Modeling (Star Schema)**
- **ETL within Power BI**

---

## 📷 Screenshots
### Dashboard
<img width="1163" height="662" alt="Screenshot 2025-09-02 143157" src="https://github.com/user-attachments/assets/b0806c39-ef44-49a1-9da5-d254e60b6170" />

### Data Model
<img width="1094" height="636" alt="Screenshot 2025-09-02 143757" src="https://github.com/user-attachments/assets/e7831306-32cf-479a-93b2-473b50e66049" />


---

## 🔑 Key Learnings
- Building a **star schema model** for sales analytics.  
- Using **DAX calculations** for profit % and YoY comparisons.  
- Designing a **user-friendly dashboard** with KPIs and drill-down capabilities.  

---

## 📌 How to Use
1. Download the `.pbix` file from this repository.  
2. Open it in **Power BI Desktop**.  
3. Explore the interactive visuals and apply filters (e.g., date range, geography).  

---

## 📬 Contact
If you have any questions or suggestions, feel free to connect!  

---
⭐ If you like this project, don’t forget to **star this repository**!
