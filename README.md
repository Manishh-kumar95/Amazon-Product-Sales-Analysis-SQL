# 🛒 Amazon Product Sales Analysis using SQL

![SQL](https://img.shields.io/badge/Language-SQL-blue?style=for-the-badge&logo=mysql)
![E-commerce](https://img.shields.io/badge/Domain-E--commerce-orange?style=for-the-badge)
![Data Analysis](https://img.shields.io/badge/Focus-Data_Analysis-green?style=for-the-badge)

## 🎯 Project Overview
This project involved analyzing Amazon product sales data to extract meaningful business insights related to pricing, discounts, and customer sentiment. The primary objective was to use SQL queries to support data-driven decision making in the e-commerce domain.

## 📊 Dataset Summary
* **Source:** Amazon product sales data
* **Total Rows:** 1465
* **Unique Products:** 1337
* **Key Columns:** `product_name`, `category`, `price`, `discount`, `rating`, `reviews`

---

## 💻 SQL Concepts Applied
This analysis utilized fundamental and advanced SQL concepts to query and aggregate the data.

* **Filtering:** Applied `WHERE`, `LIKE`, and `BETWEEN` clauses to segment data (e.g., finding products below a certain price or within a discount range).
* **Aggregation & Grouping:** Used aggregate functions like `AVG()` in combination with `GROUP BY` and `ORDER BY` to calculate metrics like the average price difference per product.
* **Pattern Matching:** Used the `LIKE` operator to query reviews for specific sentiment terms (e.g., "fast charging," "worst").

---

## 🔍 Key Business Insights
The SQL analysis revealed several actionable insights for management:

* **Pricing Strategy:** The analysis calculated the difference between average actual and discounted prices per product, showing the highest difference for "Sony Bravia 164 cm...".
* **Discount Trends:** Many products in the Cables & Accessories categories feature steep discounts of 50% or more.
* **Customer Sentiment:**
    * **Positive:** Customers frequently highlight "fast charging" in their reviews.
    * **Negative:** Queries identified key negative terms used by customers, including "worst," "waste," and "poor".
* **Data Quality Note:** The dataset contained duplicate product entries (1465 rows vs. 1337 unique products).

---

## ✅ Learning Outcomes
* Wrote complex queries to extract meaningful insights.
* Analyzed prices, discounts, ratings, and reviews to understand product performance.
* Gained experience in identifying pricing strategies and customer feedback using SQL.

---
### **👤 Submitted By: Manish Kumar**
