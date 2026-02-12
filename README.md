# 📊 Customer Behaviour Dashboard  
### Business Intelligence Project using Power BI

---

## 📌 Project Overview

The **Customer Behaviour Dashboard** is an interactive Business Intelligence solution developed using **Power BI** to analyze customer purchasing patterns, subscription behavior, revenue distribution, and category-wise sales performance.

This project demonstrates the ability to transform raw transactional data into actionable business insights through structured analysis, KPI modeling, and effective data visualization.

---

## 🎯 Business Objective

Retail businesses require clear visibility into:

- Revenue-driving product categories  
- Customer subscription adoption rate  
- Impact of discount strategies  
- Customer satisfaction trends  
- Demographic-based purchasing behavior  

This dashboard provides a centralized analytical view to support **data-driven decision-making**.

---

## 📊 Key Performance Indicators (KPIs)

- **Average Purchase Amount:** `$59.76`  
- **Average Customer Rating:** `3.75 / 5`  
- **Total Customers:** `3,900+`  
- **Subscription Distribution:** `27% Subscribed | 73% Non-Subscribed`  

---

## 📈 Dashboard Features

### 🔹 1. Executive KPI Cards
- Average Purchase Value  
- Average Review Rating  
- Total Customer Count  

### 🔹 2. Revenue Analysis
- Category-wise revenue comparison  
- Sales distribution across:
  - Clothing  
  - Accessories  
  - Footwear  
  - Outerwear  

### 🔹 3. Customer Insights
- Subscription vs Non-Subscription distribution (Donut Chart)  
- Discount impact analysis  
- Gender-based segmentation  

### 🔹 4. Interactive Filters
- Subscription Status  
- Gender  
- Discount Applied  
- Product Category  

These slicers allow dynamic and real-time data exploration.

---

## 🛠️ Tools & Technologies Used

- **Power BI** – Dashboard Development  
- **DAX (Data Analysis Expressions)** – KPI Calculations  
- **Microsoft Excel / CSV** – Data Preprocessing  
- **Data Cleaning Techniques**
  - Handling missing values  
  - Removing duplicates  
  - Data type transformation  
  - Data aggregation  

---

## 🧮 DAX Measures Implemented

```DAX
Average Purchase Amount = AVERAGE(Purchase_Amount)

Average Rating = AVERAGE(Review_Rating)

Total Customers = DISTINCTCOUNT(Customer_ID)
