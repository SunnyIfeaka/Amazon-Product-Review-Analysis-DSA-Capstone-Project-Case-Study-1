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
- **Cleaned for analysis**: 1,352 unique products  
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
  - Slicers
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

---

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
