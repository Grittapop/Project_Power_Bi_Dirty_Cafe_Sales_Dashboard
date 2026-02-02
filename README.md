# ☕ Dirty Cafe Sales Dashboard (Power BI)

## 📌 Project Overview
This project presents an **Executive Sales Dashboard** built using **Power BI**, based on a dirty café sales dataset.  
The main objective is to demonstrate **data modeling, data cleaning, DAX measures, and business storytelling** through an interactive dashboard.

The dashboard provides high-level insights into sales performance, customer behavior, product contribution, and payment methods to support data-driven decision-making.

---

## 📸 Dashboard Preview

![Dirty Cafe Sales Dashboard](https://github.com/user-attachments/assets/c5d2c31e-ef0d-43c8-a1ff-5dd7ba59c01c)

---

## 📊 Dashboard Highlights
Key metrics and insights included in the dashboard:

- **Total Sales**
- **Total Transactions**
- **Total Quantity Sold**
- **Average Order Value (AOV)**
- **Month-over-Month (MoM) Growth**
- **Sales Trend by Month**
- **Top Performing Items**
- **Sales Contribution by Item**
- **Transactions by Payment Method**
- **Performance by Location (In-store vs Takeaway)**

---

## 🧱 Data Model
The project uses a **Star Schema** data model for optimal performance and scalability.

![Data Model Imge](https://github.com/user-attachments/assets/23436014-5259-4aed-b419-32dba1e7735b)

### Fact Table
- **Fact_Sales**
  - Date  
  - Item ID  
  - Location ID  
  - Payment Method ID  
  - Quantity  
  - Price Per Unit  
  - Total Spent  

### Dimension Tables
- **Dim_Date** – Date hierarchy for time analysis  
- **Dim_Item** – Product-level analysis  
- **Dim_Location** – In-store vs Takeaway  
- **Dim_Payment** – Payment method analysis  

All relationships follow **1-to-many, single-direction** best practices.

---

## 🧹 Data Preparation
The dataset contains several data quality issues, including:
- Missing values
- `UNKNOWN` categories
- Incorrect or error values in sales fields

Data cleaning and transformation were performed using **Power Query**, and key metrics were recalculated using **DAX** to ensure accuracy.

---

## 🧮 Key DAX Measures
Examples of core measures used in the dashboard:

- Total Sales
- Total Transactions
- Total Quantity
- Average Order Value (AOV)
- Month-over-Month Growth (%)
- Sales Contribution (%)

These measures enable flexible slicing by date, item, location, and payment method.

---

## 🎯 Business Value
This dashboard helps stakeholders to:
- Monitor overall sales performance
- Identify top-selling and underperforming items
- Understand customer payment preferences
- Compare sales channels (In-store vs Takeaway)
- Track growth trends over time

---

## 🛠 Tools & Technologies
- **Power BI**
- **DAX**
- **Power Query**
- **Star Schema Data Modeling**

---

## 👤 Author
Created as a data analytics portfolio project to demonstrate end-to-end BI development skills.

