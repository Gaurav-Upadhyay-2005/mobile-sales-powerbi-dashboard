# 📊 Mobile Phone Sales Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

> An interactive sales analytics dashboard built in Power BI, designed to track mobile phone sales performance across multiple dimensions — with Month-To-Date (MTD) reporting and Same Period Last Year (SPLY) comparisons.

🔗 **[View Live Dashboard](https://app.powerbi.com/links/Byh__SeHCN?ctid=2b2b513a-7b2f-4675-97fe-08cf1ee35bd3&pbi_source=linkShare)**

---

## 📸 Dashboard Preview

### 🏠 Main Dashboard
![Main Dashboard](assests/Screenshot_2026-04-25_224945.png)

### 📅 MTD Report
![MTD Report](assests/Screenshot_2026-04-25_225201.png)

### 📆 Same Period Last Year
![Same Period Last Year](assests/Screenshot_2026-04-25_225331.png)

---

## 📌 Project Overview

This dashboard analyzes **3,835 transactions** of mobile phone sales data to help business stakeholders monitor key performance indicators in real time, compare trends across time periods, and make data-driven decisions.

---

## 📁 Dataset

| Detail | Info |
|--------|------|
| **File** | `data/Mobile_Sales_Data.xlsx` |
| **Rows** | 3,835 transactions |
| **Columns** | 14 fields |
| **Fields** | Transaction ID, Day, Month, Year, Day Name, Brand, Units Sold, Price Per Unit, Customer Name, Customer Age, City, Payment Method, Customer Ratings, Mobile Model |

---

## 📄 Dashboard Pages

### 1. 🏠 Main Dashboard
The primary overview page featuring:
- **KPI Cards** — Total Sales, Total Quantity, Total Transactions, Average Price
- **Map Visual** — Geographic distribution of sales across cities (Mumbai, Lucknow, Hyderabad, Rajkot, Indore, Kanpur)
- **Line Chart** — Monthly quantity trend (Jan–Dec)
- **Bar Chart** — Total Sales by Mobile Model
- **Pie Chart** — Transactions by Payment Method
- **Funnel Chart** — Rating by Rating Status
- **Area Chart** — Total Sales by Day Name
- **Data Table** — Brand-wise Sales & Transactions
- **Slicers** — Filter by Mobile Model, Payment Method, Brand, Month

### 2. 📅 MTD Report (Month-To-Date)
Tracks current month's cumulative performance:
- Running MTD sales line chart (daily granularity)
- KPI cards updated dynamically with MTD values
- Slicers for Mobile Model, Payment Method, Year

### 3. 📆 Same Period Last Year (SPLY)
Year-over-Year comparison featuring:
- Clustered column charts: Total Sales vs SPLY by Year, Month, Quarter
- Comparison table with exact figures
- Slicers for flexible period selection

---

## 📊 Key Measures (DAX)

| Measure | Description |
|---------|-------------|
| `Total_Sales` | Sum of all sales revenue |
| `Total_Quantity` | Total units sold |
| `Transaction` | Count of total transactions |
| `Average_Price` | Average selling price per unit |

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard development
- **DAX** — Custom measures and time intelligence calculations
- **Power Query (M)** — Data transformation and cleaning
- **Power BI Service** — Cloud publishing and sharing
- **Microsoft Excel** — Source dataset

---

## 🚀 How to Use

1. Download the `.pbix` file from this repository
2. Open with **Power BI Desktop** (free download from Microsoft)
3. Explore the 3 dashboard pages using the tab navigation
4. Use slicers to filter by date, region, or product category
5. Or view the **[live published version](https://app.powerbi.com/links/Byh__SeHCN?ctid=2b2b513a-7b2f-4675-97fe-08cf1ee35bd3&pbi_source=linkShare)** directly in browser

---

## 👤 Author

**Gaurav Upadhyay** — B.Sc. Data Science | S.M. Shetty College, Mumbai (CGPA: 9.76/10)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/gaurav-upadhyay-g)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github)](https://github.com/Gaurav-Upadhyay-2005)
