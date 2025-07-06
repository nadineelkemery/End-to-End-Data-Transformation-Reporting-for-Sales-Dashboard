# End-to-End Sales Dashboard | SQL + Power BI
Transformed raw sales data from AdventureWorksDW using T-SQL, then built a professional, interactive Power BI dashboard. Delivered dynamic insights comparing actual vs. budget sales—filterable by product, customer, time, and salesperson.
Tools: SQL Server, Power BI, DAX, Power Query, Excel.

## Objective

Deliver a clean, interactive dashboard that compares **actual sales vs. budget**, allowing filtering by **product, customer, time**, and **salesperson** — replacing static reports with actionable insights.

---

## Business Request

The sales manager wanted:
- A **dynamic dashboard** instead of static Excel reports.
- Sales breakdown by **product**, **customer**, and **time**.
- Ability to **filter by salesperson**.
- Visual comparison of **actual vs. 2021 budget** sales.

---

## Tools & Technologies

- **SQL Server** – Data extraction & transformation (T-SQL)
- **Power BI** – Data modeling, DAX, dashboard visuals
- **Power Query** – Data import & shaping
- **Excel** – CSV handling & budget data
- **DAX** – Calculated measures & KPIs
- **Star Schema** – Fact & dimension modeling

---

## Project Workflow

### 1. Data Cleaning (SQL)
- Extracted data from `AdventureWorksDW`:
  - `FactInternetSales`, `DimDate`, `DimProduct`, `DimCustomer`
- Cleaned and joined data using **T-SQL**.
- Created readable fields (`FullName`, etc.)
- Filtered for sales in the **last 2 years**.
- Exported clean datasets to **CSV**.

### 2. Power BI Dashboard
- Built **Star Schema** data model.
- Created DAX measures:
  - `Total Sales`, `Budget`, `Variance %`, `KPIs`
- Designed visuals:
  - Bar, line, donut charts, map
- Added filters for **year, month, city, product, salesperson**.
- Published via **Power BI Service**.

---

##  Outcome

  Delivered a clean, dynamic dashboard that helps sales teams:
- Monitor performance vs. budget  
- Analyze top products, cities, and customer segments  
- Make faster, data-driven business decisions  

---


