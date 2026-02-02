# ☕ Dirty Cafe Sales – Executive Dashboard (Power BI)

## 📌 Project Overview
This project presents an **Executive Sales Dashboard** built using **Power BI**, based on a publicly available café sales dataset.

The objective of this project is to demonstrate an **end-to-end Business Intelligence workflow**, including:
- Data cleaning and preparation
- Star schema data modeling
- DAX measure creation
- Executive-level dashboard design
- Business insight storytelling

To focus on insights and presentation, the final dashboard is shared as a **PDF report** rather than the Power BI (.pbix) file.

---

## 🧱 Data Source & Attribution

### Data Source
- **Dataset Name:** Cafe Sales – Dirty Data for Cleaning Training  
- **Author:** Ahmed Mohamed  
- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training  

---

### Dataset Description
The dataset contains **simulated transaction-level sales data** for a café business.  
It was intentionally designed as **dirty data** for training and practice purposes.

The dataset includes:
- Transaction ID  
- Item sold (e.g., Coffee, Cake, Cookie)  
- Quantity and price per unit  
- Total amount spent  
- Payment method  
- Sales location (In-store / Takeaway)  
- Transaction date  

To reflect real-world data challenges, the dataset contains:
- Missing values  
- Inconsistent categorical values (e.g., `UNKNOWN`)  
- Invalid numeric entries (e.g., `ERROR`)  
- Data type inconsistencies  

---

### Data Usage Disclaimer
This project is created for **educational and portfolio purposes only**.  
The dataset is publicly available and **does not represent the actual performance of any real café or business**.  
No personally identifiable information (PII) is included.

---

## 🧹 Data Preparation
Data preparation and cleaning were performed to ensure analytical accuracy and usability.

Key steps include:
- Handling missing and invalid values
- Standardizing categorical fields
- Correcting or recalculating sales-related fields
- Creating clean dimension tables for analysis

All transformations were performed using **Power Query**.

---

## 🧱 Data Model
The dashboard is built using a **Star Schema** data model to ensure performance and scalability.

![Data Model](https://github.com/user-attachments/assets/0f564700-77c1-41b3-86ff-8d26cc0dd7c9)

### Fact Table
- **Fact_Sales**
  - Date  
  - Item ID  
  - Location ID  
  - Payment Method ID  
  - Quantity  
  - Price Per Unit  
  - Total Sales  

### Dimension Tables
- **Dim_Date** – Date and time attributes  
- **Dim_Item** – Menu item details  
- **Dim_Location** – Sales channel (In-store / Takeaway)  
- **Dim_Payment** – Payment method information  

All relationships follow **one-to-many, single-direction** best practices.

---

## 🧮 Key Metrics & DAX Measures
The dashboard includes key business metrics such as:
- Total Sales
- Total Transactions
- Total Quantity Sold
- Average Order Value (AOV)
- Month-over-Month (MoM) Growth
- Sales Contribution by Item

These measures allow dynamic filtering across date, product, location, and payment method dimensions.

---

## 📊 Dashboard Overview
The executive dashboard provides insights into:
- Overall sales performance
- Monthly sales trends
- Top-performing menu items
- Sales contribution by product
- Payment method preferences
- Sales distribution by location

The layout is designed to support **quick decision-making** by business stakeholders.

---

## 🎯 Business Insights
Key insights derived from the dashboard include:
- Sales show consistent month-over-month growth
- A small number of products contribute a large share of total revenue
- Digital payment methods slightly outperform cash transactions
- In-store and takeaway sales volumes are relatively balanced

---

## 🛠 Tools & Technologies
- **Power BI**
- **DAX**
- **Power Query**
- **Star Schema Data Modeling**

---

## 📸 Dashboard Preview

![Dirty Cafe Sales Dashboard](https://github.com/user-attachments/assets/a1381f80-dc8a-4fc9-8892-43e5f808e389)

---

## 👤 Author
This project was created as part of a **data analytics portfolio** to demonstrate practical skills in business intelligence, data modeling, and dashboard storytelling.

