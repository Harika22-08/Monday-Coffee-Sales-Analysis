# Monday-Coffee-Sales-Analysis
From beans to business: SQL-driven story of where Monday Coffee should pour its next cup.

# ☕ Sales Analysis for **Monday Coffee**  
### 🔍 Data-driven Store Expansion Strategy using **SQL**

## 🎯 Project Objective

The aim of this project is to analyze the online sales performance of **Monday Coffee**, active since **January 2023**, and recommend the **top 3 cities in India** to open new physical store locations based on:

- 📈 Consumer Demand  
- 💰 Sales Performance  
- 🏢 Cost-efficiency

---

## 🗃️ Dataset Overview

This project utilizes four key datasets:

| 📋 Table | 🧾 Description |
|---------|----------------|
| `city` | Contains city-wise population, average rent, and ranking data |
| `products` | Coffee product catalog with pricing |
| `customers` | Customer demographics and associated cities |
| `sales` | Transactional sales data: date, product, customer, amount, rating |

---

## 📊 Key Analyses Performed

1. 🧍‍♂️ **Estimated Coffee Consumers**  
   - Identified top cities assuming **25% of the population** are potential coffee drinkers.

2. 💵 **Total Revenue (Q4 2023)**  
   - Analyzed total sales from **October to December 2023**.

3. ☕ **Top-Selling Products**  
   - Ranked products based on units sold.

4. 🧾 **Avg. Sales per Customer per City**  
   - Measured customer spending power in each city.

5. 📉 **Estimated vs. Actual Buyers**  
   - Compared projected vs. actual number of buyers city-wise.

6. 🏙️ **Top 3 Products in Each City**  
   - Identified bestselling products in each city by volume.

7. 👥 **Unique Customers by City**  
   - Counted distinct customers across cities.

8. 💸 **Average Rent vs Revenue per Customer**  
   - Assessed profitability by comparing rent to revenue per customer.

9. 📆 **Sales Growth Rate (Monthly)**  
   - Tracked monthly growth/decline in total revenue.

10. 🏆 **Top 3 Cities for New Store Openings**  
    - Final recommendations based on multi-criteria scoring.

---

## 🏁 Final Recommendations

### ✅ Best Cities to Open a Physical Store:

#### 📍 **1. Pune**
- 💰 **Total Revenue:** ₹1.25M  
- 📊 **Avg. Sales per Customer:** ₹24,197.88  
- 🏠 **Rent per Customer:** ₹294.23

#### 📍 **2. Delhi**
- 👥 **Estimated Coffee Consumers:** 7.75M  
- 👤 **Unique Customers:** 68  
- 🏠 **Rent per Customer:** ₹330.88

#### 📍 **3. Jaipur**
- 👤 **Highest Customer Count:** 69  
- 🏠 **Lowest Rent per Customer:** ₹156.52  
- 💳 **Avg. Sales per Customer:** ₹11,644.20

---

> 🔎 This project showcases the power of **SQL-based decision-making** by combining customer analytics, sales data, and city-level cost metrics to generate smart, data-driven expansion strategies.

---
