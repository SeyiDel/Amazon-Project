# 📁 Project Overview
This project involves a comprehensive Excel-based analysis of Amazon product data. The dataset contains information scraped from Amazon product pages, including product attributes, pricing, discounting, customer engagement, and review data. The objective is to extract meaningful insights through pivot tables, calculated columns, and Excel functions.
# 📊 Dataset Description

| Property          | Details                                       |
| ----------------- | --------------------------------------------- |
| **Source**        | Web-scraped Amazon product listings           |
| **Records**       | 1,465 rows                                    |
| **Fields**        | 16 columns                                    |
| **Structure**     | Each row represents a unique product          |
| **Data Includes** |                                               |
| → Product Name    | Text (title of the product)                   |
| → Category        | Product category                              |
| → Original Price  | MRP or listed price before discount           |
| → Discount (%)    | Calculated percentage discount                |
| → Actual Price    | Final selling price after discount            |
| → Rating          | Average product rating (e.g., 4.3)            |
| → Rating Count    | Total number of customer ratings              |
| → Review Titles   | Comma-separated titles from user reviews      |
| → Review Content  | Comma-separated full review text (aggregated) |

# 🔍 Analysis Objectives
Using Pivot Tables, Calculated Columns, and Filtering, the following tasks are performed:

- Average discount percentage by product category
- Product count per category
- Total number of reviews per category
- Top-rated products by average rating
- Average actual price vs. original price by category
- Products with the highest number of reviews
- Count of products with ≥ 50% discount
- Distribution of product ratings (e.g., 3.0, 4.0, etc.)
- Total potential revenue (actual_price × rating_count) by category
- Unique product count per price bucket:
-- < ₹200
-- ₹200–₹500
-- > ₹500
- Relationship between discount level and product rating
- Products with fewer than 1,000 reviews
- Categories with the highest average discounts
- Top 5 products ranked by combined rating and review volume

# 🛠️ Excel Tools & Features Used
✅ Pivot Tables
✅ Calculated Fields (e.g., Discount %, Revenue)
✅ Price Bucketing using IF and VLOOKUP / XLOOKUP
✅ Conditional Formatting (for highlighting top/bottom performers)
✅ Sorting & Filtering

# 📌 Notes
-All analysis was conducted using Microsoft Excel
- Ratings and reviews are pre-aggregated from scraping — each row is not per individual customer but per product.
- Currency is assumed to be Indian Rupees (₹).


