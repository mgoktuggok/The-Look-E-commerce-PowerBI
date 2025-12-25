# Olist / The Look E-Commerce Analytics Dashboard (Power BI)

## 📌 Project Overview
This project is a **group-based Power BI analytics project** built on an e-commerce dataset (Olist / The Look).
The dashboard provides a comprehensive view of:
- Sales performance
- Seasonal trends
- Customer behavior
- Inventory management

The primary goal is to transform raw transactional data into **decision-oriented business insights**.

---

## 🎯 Business Objectives
E-commerce platforms face multiple operational challenges:
- Understanding sales and profitability drivers
- Managing seasonal demand fluctuations
- Analyzing customer behavior and segmentation
- Optimizing inventory levels to reduce excess stock and stock-out risk

This project addresses these challenges through interactive dashboards designed for **business stakeholders**.

---

## 📊 Dashboard Structure

### 1️⃣ Sales Performance Analysis
- Total sales volume, revenue, cost, and profit KPIs
- Product-level and brand-level sales comparisons
- Category-based sales distribution
- Return rate analysis by category

Purpose:  
Provide a high-level executive view of overall business performance.

---

### 2️⃣ Seasonal Sales Analysis
- Monthly sales trends
- Seasonal order distribution (Spring, Summer, Fall, Winter)
- Category-level seasonal demand patterns

Purpose:  
Identify demand peaks and seasonality effects to support planning and forecasting.

---

### 3️⃣ Customer Behavior Analysis
- Customer distribution by gender and acquisition channel
- Spending segment analysis (low / medium / high)
- Age group–based spending patterns
- Customer lifetime segmentation and regional concentration

Purpose:  
Understand customer profiles and purchasing behavior to support growth and retention strategies.

---

### 4️⃣ Inventory Management Analysis *(Primary Responsibility)*
This page represents my **main individual contribution** to the project.

Key focus areas:
- Total products, sold products, and products remaining in stock
- Inventory ratio (stocked products / total products)
- Average inventory holding duration (in days)
- Categories with the longest stock retention periods
- Category-level stock-out risk ratios
- Brand-based inventory level comparisons
- Quarterly sales volume trends

Purpose:  
Support **inventory optimization, replenishment prioritization, and operational efficiency** by highlighting inventory pressure points.

---

## 🔧 Data Preparation & Transformation

### Data Cleaning
- Removed duplicate and invalid transaction records
- Standardized product, category, and brand identifiers
- Converted timestamp fields into proper datetime formats
- Ensured numerical consistency for quantity, price, and cost fields

### Feature Engineering
Derived columns and metrics were created to support inventory-focused analysis, including:
- Sold vs stocked product counts
- Inventory ratio calculations
- Average inventory holding duration
- Category-level inventory accumulation indicators
- Stock-out risk metrics

### DAX Measures
Custom DAX measures were developed to:
- Dynamically calculate inventory ratios
- Compare sold and stocked products across categories
- Aggregate average stock holding durations
- Enable time-based slicing (year, quarter) for inventory evaluation

These transformations were essential for translating raw data into **actionable inventory insights**.

---

## 🛠️ Tools & Technologies
- **Power BI** – Dashboard development and visualization - **DAX** – Custom measures and KPIs
- **SQL (BigQuery)** – Data extraction and aggregation
- **CSV / Excel** – Intermediate data handling
