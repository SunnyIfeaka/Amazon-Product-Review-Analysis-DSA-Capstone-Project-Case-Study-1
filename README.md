# Amazon-Product-Review-Analysis-DSA-Capstone-Project-Case-Study-1
 DSA Capstone data analysis project report for Amazon
 
##  Project Overview
This project analyzes Amazon product and customer review data to generate insights that support:

- Product improvement
- Marketing strategy refinement
- Customer engagement enhancement

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


## Key Analytical Questions & Insights
This section breaks down the findings from the 14 analytical tasks and provides specific recommendations. 

### 1. What is the average discount percentage by product category?
**Insight:** Categories such as *Home Improvements*, *Computer & Accessories*  and *Health & Personal Care* show higher average discount percentages. This could be leveraged during seasonal campaigns or flash sales to further boost visibility and conversions.
### 2. How many products are listed under each category?
**Insight:** Categories like *Electronics*, *Home & Kitchen* and *Computer & Accessories* dominate the catalog. This insight can guide inventory and merchandising decisions.
### 3. What is the total number of reviews per category?
**Insight:** *Electronics*, *Computer & Accessories*, and *Home & Kitchen* receive significantly higher review volumes, indicating higher customer engagement or more mature markets. These are good targets for review-based promotions.
### 4. Which products have the highest average ratings?
**Insight:** Products majorly in categories of *Computer & Accessories*, *Electronics*, and *Home & Kitchen* are top rated. Top-rated products often belong to niche subcategories or premium brands. These can be featured in "Amazon’s Choice" or "Recommended for You" promotions.
### 5. What is the average actual price vs. discounted price by category?
**Insight:** The average price drop is most significant in categories with high competition. Categories like *Electronics* have a significant average price drop. Competitive pricing can be a key strategy in this market.
### 6. Which products have the highest number of reviews?
**Insight:** *Amazon HDMI Cables* in the *Electronics* category have the highest number of reviews. Products with the most reviews tend to be bestsellers or flagship items. They can be bundled or cross-sold with newer products to leverage existing popularity.
### 7. How many products have a discount of 50% or more?
**Insight:** A moderate number of products are heavily discounted, mostly in *Electronics* or *Computer & Accessories*. Investigate products with high discounts for cost-justification.
### 8. What is the distribution of product ratings?
**Insight:** Most products cluster around 3.5 to 4.5 stars. Very few products are below 3.0 stars and above 4.5 stars. Very low-rated products may need attention for quality improvement or removal.
### 9. What is the total potential revenue (actual price × rating count) by category?
**Insight:** Categories like *Electronics* *Computer & Accessories*, and *Home & Kitchen* generate the highest potential revenue. This suggests where marketing budgets can be best allocated for maximum return.
### 10. What is the number of unique products per price range bucket?
**Insight:** Majority of products fall within the >₹500 range, indicating a price-sensitive customer base. Premium products should be differentiated clearly in the value proposition.
### 11. How does rating relate to the level of discount?
**Insight:** There appears to be no consistent correlation between high discount levels and ratings. Products with the highest average ratings often have lower discounts,  while products with lower average ratings often have higher discounts, suggesting quality drives reviews more than price cuts. Focus on value, not just price.
### 12. How many products have fewer than 1,000 reviews?
**Insight:** Most products in the dataset have already crossed the 1,000-review threshold, indicating a healthy level of customer engagement. However, for the smaller segment of under-reviewed products, targeted strategies such as promotions or review incentives could help improve visibility and trust.
### 13. Which categories have products with the highest discounts?
**Insight:** *Computer & Accessories*, *Electronics*, and *Home & Kitchen* products show the steepest discounts, ideal for promoting in clearance events, like Prime Day or Black Friday, or influencer marketing.
### 14. Identify the top 5 products in terms of rating and number of reviews combined.
**Insight:** These products should be spotlighted in marketing campaigns, bundled with newer SKUs, or leveraged as flagship store items.


## Recommendations

1. **Boost visibility for under-reviewed products** using incentives or Amazon Vine programs.
2. **Promote top-rated products** through Amazon ads and feature placements.
3. **Segment campaigns by price sensitivity** using the pricing bucket analysis.
4. **Review underperforming SKUs** (low rating + low review) for quality assurance.
5. **Invest marketing spend in high revenue potential categories** identified in the revenue analysis.

