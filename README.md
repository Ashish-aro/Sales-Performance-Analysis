# 📊 Sales Performance Analysis (Superstore Dataset)

## 📌 Project Overview

This project presents an **end-to-end sales performance analysis** using the **Superstore dataset**.
The objective is to analyze **sales, profit, customer behavior, shipping efficiency, and regional performance** to support data-driven business decisions.

The project uses **Excel as the raw data source** and **Power BI for modeling, DAX calculations, and interactive dashboards**.

---

## 🗂 Dataset Information

* **Source File:** `superstore.xlsx`
* **Total Records:** 51,290 rows
* **Total Columns:** 27

### Key Data Fields

| Category      | Columns                                          |
| ------------- | ------------------------------------------------ |
| Order Info    | Order.ID, Order.Date, Ship.Date, Order.Priority  |
| Customer      | Customer.ID, Customer.Name, Segment              |
| Product       | Product.ID, Product.Name, Category, Sub.Category |
| Geography     | Market, Market2, Country, Region, State, City    |
| Sales Metrics | Sales, Profit, Quantity, Discount                |
| Logistics     | Ship.Mode, Shipping.Cost                         |
| Time          | Year, weeknum                                    |

---

## 🛠 Tools & Technologies

* **Microsoft Excel** – Raw data storage and inspection
* **Microsoft Power BI** – Data modeling, DAX, and dashboard development

---

## 🔄 Data Preparation & Modeling

The following steps were applied in Power BI:

* Converted **Order Date** and **Ship Date** to proper date formats
* Created **time-based fields** (Year, Week Number)
* Validated numerical fields for **Sales, Profit, Quantity, Discount**
* Built relationships and measures for analytical reporting

### Key DAX Measures (Typical)

* Total Sales
* Total Profit
* Profit Margin (%)
* Total Orders
* Average Shipping Cost
* Average Discount

---

## 📊 Dashboard & Analysis Focus

The Power BI dashboard answers key business questions:

### 📈 Sales & Profit Analysis

* Year-wise and region-wise sales trends
* High-sales but low-profit product identification

### 🌍 Regional Performance

* Performance comparison across **Markets, Regions, and States**
* Identification of top and underperforming geographies

### 🛍 Product Analysis

* Category and Sub-Category contribution to revenue and profit
* Quantity vs Profit behavior across products

### 👥 Customer Segment Insights

* Sales and profit distribution across **Consumer, Corporate, and Home Office** segments

### 🚚 Shipping & Logistics

* Shipping cost impact by **Ship Mode**
* Delivery efficiency insights

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/sales-performance-analysis.git
   ```
2. Open **superstore.xlsx** to view raw data
3. Open **Sales Performance Analysis.pbix** in Power BI Desktop
4. Use slicers to explore:

   * Year
   * Market / Region
   * Category / Segment

---

## 🎯 Business Insights Enabled

* Identification of **profit-draining products despite high sales**
* Understanding **regional demand and profitability**
* Analysis of **discount impact on profit margins**
* Optimization opportunities in **shipping cost and order priority**

---

## 👤 Author

**Ashish Kumar**
Data Analyst | Power BI | SQL | Excel
