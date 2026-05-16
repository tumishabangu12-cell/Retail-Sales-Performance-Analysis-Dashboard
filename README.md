# Retail Sales Performance Analysis Dashboard

## 📌 Project Overview

This project presents an end-to-end data analytics and business intelligence solution designed to transform raw transactional data into actionable commercial insights. Utilizing a dataset containing 1,000 retail transactions, I engineered an interactive, high-impact **Power BI** dashboard. The primary objective of this dashboard is to optimize inventory distribution, define consumer profiles, and track revenue seasonal trends to empower executive decision-making.

---

## 🛠️ Tech Stack & Architecture

* **Business Intelligence:** Power BI Desktop (Dashboard Design, Canvas Layout Optimization, Visual Hierarchy).
* **Data Transformation:** Power Query (Data cleaning, explicit data typing, conditional column extraction).
* **Data Modeling & Analytics:** DAX (Data Analysis Expressions) for customized business intelligence measures.
* **Data Sourcing:** Structured CSV/Excel datasets.

---

## 📊 Core Business Metrics (DAX Measures)

To move past default aggregations and build an industry-standard performance tracker, the following key DAX measures were constructed:

* **Total Revenue Generated:**
```dax
Total Revenue = SUM('retail_sales_dataset'[Total Amount])

```


* **Total Sales Volume:**
```dax
Total Units Sold = SUM('retail_sales_dataset'[Quantity])

```


* **Transaction Count:**
```dax
Total Transactions = COUNT('retail_sales_dataset'[Transaction ID])

```


* **Average Transaction Value (ATV):**
```dax
ATV = AVERAGE('retail_sales_dataset'[Total Amount])

```



---

## 📈 Strategic Key Findings

* **Financial Standing:** The operation yielded a gross revenue of **$456,000** across **1,000 distinct transactions**, maintaining a strong Average Transaction Value (ATV) of **$456**.
* **Product Performance:** **Clothing** emerged as the primary revenue engine, closely followed by Electronics and Beauty, proving a robust, evenly distributed market demand across departments.
* **Demographic Breakdown:** Customer acquisition is beautifully balanced, with a purchasing distribution of **51% Female** and **49% Male** consumers.
* **Target Audience:** Peak consumer engagement and purchasing power sit firmly within the **25-50 age demographic**, pinpointing the exact audience for targeted digital marketing campaigns.

---

## 🚀 Development Step-by-Step

### 1. Data ETL & Processing

* Formatted chronological `Date` strings into structured Date types.
* Cleaned and verified categorical dimensions (`Gender`, `Product Category`) to ensure absolute accuracy.
* Engineered custom age groupings via Power Query conditional columns to group micro-demographics into actionable macro-target audiences.

### 2. UI/UX & Canvas Optimization

* Applied a rigid **F-Pattern layout design framework** to capture professional visual hierarchy, anchoring immediate focus to high-level strategic numbers.
* Implemented clean, white **Visual Containers** utilizing rounded shapes with subtle drop-shadows to eliminate clutter and mimic a modern data application.
* Normalized reporting typography and utilized a unified, professional color palette across all distribution elements.
* Maximized screen space by omitting redundant axis labels, turning on explicit data labels, and creating clean floating slicer bars for seamless time-series filtering.

---

## 📂 Repository Contents

* `Retail_Sales_Dashboard.pbix` — The complete interactive Power BI workbook file.
* `retail_sales_dataset (1).csv` — The raw transaction dataset utilized for modeling.
* `README.md` — Project methodology and detailed documentation.

---

## 💡 How to Interact with the Report

1. Ensure **Power BI Desktop** is installed on your machine.
2. Clone or download this repository locally.
3. Open the `.pbix` file.
4. Utilize the horizontal slicer panels at the top to dynamically filter the financial ecosystem by specific transaction dates or product categories.

