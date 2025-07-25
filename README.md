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
| 3  | What is the total number of reviews per category?                                | Bar of a Pie + Pivot Table                               |
| 4  | Which products have the highest average ratings?                                 | Sorting based on calculated `Average Rating`             |
| 5  | What is the actual vs discounted price by category?                              | 3-D 100% Stacked Bar Chart + Pivot Table                 |
| 6  | Which products have the highest number of reviews?                               | Pivot Table + Filter in ascending order                  |
| 7  | How many products have ≥ 50% discount?                                           | Filter on Calculated Discount column                     |
| 8  | What is the distribution of product ratings (e.g., 3.0, 4.0, etc.)?              | Pivot Table + Bar chart                                   |
| 9  | Total potential revenue (actual_price × rating_count) per category?              | Pivot Table + SUM filter                                  |
| 10 | Unique product count per price range bucket (<200, 200–500, >500)?	              | IF formulas + Donut Chart                                 |
| 11 | Relationship between rating and discount level?                                  |	Scatter Line Chart                                        |
| 12 | How many products have fewer than 1,000 reviews?	                                | COUNTIF Formula                                           |
| 13 | Categories with highest average discount?	                                      | Sorted Pivot Table by MAX of Discount%                    |
| 14 | Top 5 products by combined review count and rating	                              | Rank using SUM(Rating × ReviewCount)                      |

---

## 📊 Dashboard Preview

### 📊 Section 1: Product Distribution & Category Insight!
<img width="1624" height="774" alt="Amazon Excel Dashboard 1" src="https://github.com/user-attachments/assets/58ee92ce-53ec-4872-b00d-17668e2ce11e" />

### 📊 SECTION 2: PRICING AND DISCOUNTS
<img width="1602" height="629" alt="Amazon Dashboard 2" src="https://github.com/user-attachments/assets/1f0dfdc7-f793-4dd3-9cd4-26c91ce9254e" />

### 📊 SECTION 3: RATING AND PERFORMANCE INSIGHTS
<img width="1510" height="629" alt="Amazon Dashboard 3" src="https://github.com/user-attachments/assets/cd369a86-f51b-41b9-941e-5ac20af22f94" />

### Full Dashboard
<img width="1991" height="1696" alt="full picture" src="https://github.com/user-attachments/assets/5dcb85e9-12af-4173-a352-b688f72f2bc3" />


## 🧠 Pivot Tables
<img width="1227" height="705" alt="Pivot Tables" src="https://github.com/user-attachments/assets/af478599-a533-4dab-a047-b4f1f781a044" />

## 🌱 Raw Data Set & Table
<img width="1884" height="972" alt="Tables" src="https://github.com/user-attachments/assets/cb41716e-d18a-4011-9a54-6483d15de270" />

<img width="1887" height="956" alt="image" src="https://github.com/user-attachments/assets/ac71ee4c-96ef-4fa9-9c6f-750e792b7d62" />













> The Excel dashboard provides an interactive, visual summary using charts, slicers, and conditional formatting for trend discovery and comparative analysis.

---

## ✅ Key Takeaways
Discount ≠ High Rating: Discounts don’t guarantee better reviews.

Affordable Pricing Dominates: Most products are low to mid-priced.

Top Revenue Categories: Home Kitchen & Electronics lead.

Most Reviewed: Electronics & Accessories get the most feedback.

Top Products: AmazonBasics FI, Realme X stand out.

Biggest Discounts: Health & Home items offer the steepest cuts.

---

## ✅ Tasks Completed

- [x] Cleaned and pre-processed raw dataset  
- [x] Created multiple pivot tables to explore key metrics  
- [x] Answered 14 analytical business questions  
- [x] Designed a fully functional Excel dashboard  
- [x] Uploaded all assets and documented in GitHub

---

### 🎯 Motivation
With so many products on Amazon, understanding customer behavior through review data can help sellers improve product visibility, pricing, and satisfaction. This project was designed to simulate a real-world business case as a Junior Data Analyst.

---

### 👋 Let’s Connect
If you’d like to collaborate or have feedback, feel free to reach out!

📧 Email: hephzibah200829@gmail.com  
📱 LinkedIn: [Boluwatife Amu](https://linkedin.com/in/boluwatife-amu-15a1b0287)



