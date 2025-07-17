# 📦 Amazon Product Review Analysis

## 🔍 Overview

This project simulates a real-world data analytics task at *RetailTech Insights*, a company offering e-commerce analytics solutions to sellers on platforms like Amazon.

As a Junior Data Analyst, I analyzed product and customer review data to generate insights that guide product improvements, marketing strategies, and customer engagement. The entire analysis was done using **Microsoft Excel** — from data cleaning to dashboard creation.

---

<details>
<summary>🏢 <strong>Project Context</strong></summary>

**Client:** *RetailTech Insights*  
**Industry:** *E-commerce Analytics*  
**Role:** *Junior Data Analyst*  
**Tools & Techniques Used:**  
- Microsoft Excel (Pivot Tables, Charts, Conditional Formatting, Slicers, Cards)  
- Data Cleaning and Transformation  
- Dashboard Design and Storytelling  
- Exploratory Data Analysis (EDA)

</details>

---

## 📁 Dataset Description

The dataset contains product and customer review information scraped from Amazon product pages:

- **Product Details:** name, category, price, discount, and ratings  
- **Customer Engagement:** user reviews, content, and titles  
- Each row represents a **unique product**, with aggregated reviewer data

📊 **Records:** 1,351 rows  
🧮 **Fields:** 16 columns  

---

## 🎯 Analysis Goals

Using Excel pivot tables and calculated columns, I explored and answered:

1. What’s the average discount percentage by product category?  
2. How many products are listed under each category?  
3. What is the total number of reviews per category?  
4. Which products have the highest average rating?  
5. What’s the average actual price vs the discounted price per category?  
6. Which products have the highest number of reviews?  
7. How many products have discounts of 50% or more?  
8. What’s the distribution of product ratings (e.g., 3.0, 4.0, etc.)?  
9. What is the total potential revenue (`actual_price * rating_count`) by category?  
10. What is the number of unique products per price range bucket?  
11. How does rating relate to the level of discount?  
12. How many products have fewer than 1,000 reviews?  
13. Which categories have the highest discounts?  
14. Identify the top 5 products by rating and number of reviews combined.

---

## 📊 Key Analytical Tasks & Solutions

| #  | Task Description                                                                 | Excel Tools / Logic Used                                |
|----|----------------------------------------------------------------------------------|----------------------------------------------------------|
| 1  | What is the average discount % by product category?                              | Pivot Table + Average Formula                            |
| 2  | How many products are listed under each category?                                | Pivot Table + Count                                      |
| 3  | What is the total number of reviews per category?                                | SUM of `Rating Count` by category                        |
| 4  | Which products have the highest average ratings?                                 | Sorting based on calculated `Average Rating`             |
| 5  | What is the actual vs discounted price by category?                              | Grouped Bar Chart + Pivot Summary                        |
| 6  | Which products have the highest number of reviews?                               | Top-N Analysis using Sorting + Pivot Table               |
| 7  | How many products have ≥ 50% discount?                                            | Filter logic on Discount column                          |
| 8  | What is the distribution of product ratings (e.g., 3.0, 4.0, etc.)?              | Grouped Histogram with Pivot Count                       |
\

---

## 📊 Dashboard Preview

![Dashboard Preview](./visuals/dashboard_preview.png) <!-- Replace with your actual path/screenshot -->

> The Excel dashboard provides an interactive, visual summary using charts, slicers, and conditional formatting for trend discovery and comparative analysis.

---

## 🧠 Key Insights

- 📈 *Electronics* and *Home Appliances* had the highest review counts, indicating strong customer engagement.  
- 💸 *Fashion* products offered the largest discounts, averaging over 40%.  
- ⭐ Products with the highest ratings were not always those with the most reviews — showing potential niche product popularity.  
- 🛍️ High discount rates didn’t guarantee high ratings — suggesting that pricing alone isn’t enough for customer satisfaction.

---

## ✅ Tasks Completed

- [x] Cleaned and pre-processed raw dataset  
- [x] Created multiple pivot tables to explore key metrics  
- [x] Answered 14 analytical business questions  
- [x] Designed a fully functional Excel dashboard  
- [x] Uploaded all assets and documented in GitHub

---

## 📂 Repository Structure


