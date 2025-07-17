# Amazon-Product-Review-Analysis-DSA-Capstone-Project-Case-Study-1
 DSA Capstone data analysis project report for Amazon
 
##  Project Overview
This project analyzes Amazon product and customer review data to generate insights that support:

- Product improvement
- Marketing strategy refinement
- Customer engagement enhancement

The analysis was done using Microsoft Excel, with advanced functions, pivot tables, charts, and a final interactive dashboard.
---

##  Dataset Description

- **Source**: Scraped Amazon data  
- **Records**: 1,465 total products  
- **Cleaned for analysis**: 1,351 unique products  
- **Columns Included**:
  - Product ID
  - Product Name
  - Category (Main and Subcategories)
  - Actual Price
  - Discounted Price
  - Discount Percentage
  - Rating (Average)
  - Rating Count (Total Reviews)

---
##  Tools Used

- **Microsoft Excel**
  - Pivot Tables
  - Conditional Formatting
  - Charts (Bar, Column, Pie)
  - Dashboard Design
- **GitHub** *(for documentation and project hosting)*

 
 ## Data Cleaning Summary
### Performed in Excel:
- Removed duplicate product IDs  
- Parsed and separated concatenated categories  
- Standardized price and rating formats  
- Created calculated fields for:
  - Discount %
  - Potential Revenue (`Actual Price × Rating Count`)
  - Review Buckets
  - Discount Buckets
  - Combined Review Score (`Rating + (Review Count ÷ Scaling Factor)`)
---

##  Analysis Tasks and Insights

### Key Analytical Questions
1. What is the average discount percentage by product category? 
2. How many products are listed under each category? 
3. What is the total number of reviews per category?  
4. Which products have the highest average ratings? 
5. What is the average actual price vs the discounted price by category? 
6. Which products have the highest number of reviews? 
7. How many products have a discount of 50% or more? 
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)? 
9. What is the total potential revenue (actual_price × rating_count) by category? 
10. What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)? 
11. How does the rating relate to the level of discount? 
12. How many products have fewer than 1,000 reviews? 
13. Which categories have products with the highest discounts? 
14. Identify the top 5 products in terms of rating and number of reviews combined.


## 💡 Insights & Recommendations

### 📦 Product Improvement
- Several products rated below 3.5 despite deep discounts — may require quality review or de-listing
- Hidden gems (rating ≥ 4.5 but < 500 reviews) should be promoted more aggressively

### 🎯 Marketing Strategy
- Electronics generated the highest potential revenue — ideal for ad targeting
- Home & Kitchen had many products with high reviews and moderate discounts — stable performer

### 👥 Customer Engagement
- 65%+ of products had <1,000 reviews — visibility is a concern
- Use influencer marketing, sponsored ads to boost engagement for quality products with low reach


Electronics dominate in revenue but also show high return rates — possible quality concerns.

52% of products have under 1,000 reviews, indicating a need for better visibility or promotion.

Some low-rated products are still heavily discounted — a flag for poor value perception.

A few standout products drive a large share of reviews and positive sentiment — ideal for spotlighting in marketing.



## 📊 Dashboard Overview

The interactive dashboard presents summarized KPIs, charts, and tables, allowing stakeholders to quickly grasp product-level insights.

### Key Features

| Section | Description |
|--------|-------------|
| 🏆 **Top Products** | Ranked by a combined score of rating × reviews |
| 💰 **Top Revenue Categories** | Which categories contribute most to potential revenue |
| 🔍 **Low-rated Products** | Products with rating < 3.5 for quality attention |
| 🧨 **High Discount + Low Rating** | Products needing steep pricing despite poor reviews |
| 📉 **Most Returned Products** | If available, shows dissatisfaction or expectation gap |
| 🗣️ **Rating Distribution** | Understand customer sentiment at a glance |
| 🧍 **% with <1,000 Reviews** | Discoverability and visibility insight |
| 📦 **Influential Products** | Rating × Reviews highlights power products |

---

## 📌 Key Performance Indicators (KPIs)

| KPI | Description | Icon |
|-----|-------------|------|
| 📦 **Total Products** | Total number of unique products analyzed | ![#](https://img.icons8.com/color/amazon-icon.png) |
| ⭐ **Average Rating** | Average customer rating across products | 🟠 |
| 💬 **Total Reviews** | Total number of reviews accumulated | 💭 |
| 💵 **Total Potential Revenue** | Sum of all expected product revenues | 💰 |
| 🔎 **Products with <1,000 Reviews (%)** | Products with low engagement visibility | 📉 |

---

## 📈 Insights & Recommendations

### ✅ Product Improvement
- Target low-rated products (<3.5) for quality upgrade.
- Investigate products with high returns or discounts for cost-justification.

### 📢 Marketing Strategy
- Focus ad spend on top revenue-generating categories.
- Leverage high influence products (high rating × reviews) in promotions.

### 👥 Customer Engagement
- Improve visibility for products with <1,000 reviews via campaigns.
- Rating distribution suggests overall customer satisfaction is **X% positive** (optional if analyzed).

---

## 🔄 Suggested Improvements

- Include **date/timestamp** to track trends over time.
- Add **return rate column** if data permits.
- Incorporate **competitor benchmarks** for deeper comparisons.
- Automate updates using Power Query (future iteration).

---

## 🗂️ File Structure

```bash
Amazon-Excel-CaseStudy/
│
├── 📁 Data/
│   └── amazon_products.xlsx
│
├── 📁 Dashboard/
│   └── amazon_dashboard.xlsx
│
├── 📁 Images/
│   └── dashboard_screenshot.png
│
├── README.md
