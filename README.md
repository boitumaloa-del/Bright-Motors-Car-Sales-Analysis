<h1>🏎️ Bright Motors Car Sales Analysis </h1>  

This repository contains the full end-to-end data analytics project for the Bright Motors Car Sales Analysis case study.
The objective of this project is to help the newly appointed Head of Sales understand historical performance, identify key revenue drivers, and uncover opportunities to improve dealership profitability.

# 📁 **Repository Structure**

```
BrightMotors-Car-Sales-Analysis/
│
├── 1. Provided Information/
│     └── Instruction Manual.pdf
│     └── Raw Data.csv
│
├── 2. Planning/
│     ├── Miro Architecture Diagram
│     └── Gantt Chart (Canva)
│
├── 3. Analysis/
│     ├── Snowflake SQL/
│     │     └── car_sales_queries.sql
│     └── Excel Visualisations/
│           └── car_sales_processed.xlsx
│
└── 4. Presentation/
      └── BrightMotors_Presentation.pptx
```

---

# 🎯 **Project Objective**

Using the historical car sales dataset, the analysis focuses on identifying:

* Which **car makes and models** generate the highest revenue
* How **price, mileage, and manufacturing year** relate to each other
* **Regional sales performance** (city/province comparison)
* **Trends in customer purchasing behaviour**
* Strategic **recommendations** for improving profitability and inventory planning

---

# 🛠️ **Tools & Technologies Used**

### **Data Processing**

* Snowflake SQL
* Microsoft Excel (data cleaning and export)

### **Planning & Architecture**

* Miro (data flow, processing architecture)
* Canva (Gantt chart)

### **Visualisation**

* Microsoft Excel 
* Pivot tables & charts

### **Presentation**

* Microsoft PowerPoint

---

# 🔄 **Workflow Overview**

### **1. Planning (Miro + Gantt Chart)**

* Data flow diagram
* SQL transformation plan
* Project timeline

### **2. Snowflake SQL Analysis**

Key steps included:

* Data cleaning (removing commas, converting prices to numeric)
* Adding calculated fields:

  * `total_revenue = selling_price * units_sold`
  * `profit_margin = (selling_price - cost_price) / selling_price * 100`
* Categorising margin bands (High, Medium, Low)
* Grouping by:

  * Make, Model
  * Region
  * Year
  * Transmission Type
* Exporting processed dataset for Excel visualization

### **3. Excel Visualisation**

* Pivot tables for:

  * Monthly Price Trends
  * Sales by region
  * Transmission type distribution
  * Year-over-year trends
* Interactive slicers

### **4. Presentation (PowerPoint)**

Final presentation summarises:

* Insights
* Trends
* KPI results
* Recommendations for the Head of Sales

---

# 📊 **Key Insights (High-Level Summary)**

* Certain makes/models dominate revenue because of high selling prices and strong demand.
* Older vehicles with higher mileage show predictable price drops.
* Specific regions consistently outperform others, indicating strong dealership clusters.
* Fuel type trends reflect a shift in customer preferences (e.g., rise of hybrids/electric).
* Inventory profitability is tied closely to margin categories and demand hotspots.

---



