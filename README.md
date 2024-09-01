# RFM Analysis for Customer Segmentation

## Introduction

This project focuses on RFM (Recency, Frequency, Monetary) analysis, a powerful tool for customer segmentation. By understanding customer purchase behavior, this analysis helps to identify key segments for targeted marketing, ultimately driving business growth and customer retention.

## Problem Statement

Understanding customer behavior is crucial for developing effective marketing strategies. However, without proper segmentation, marketing efforts may be misaligned, leading to wasted resources and missed opportunities. The challenge is to segment customers in a way that allows for personalized marketing that resonates with different customer groups.

## Objective
- Calculate the recency, frequency, and monetary value for each customer.
- Assign RFM scores to each customer to classify them into segments.
- Visualize the RFM segments to provide stakeholders with actionable insights.
- Utilize these insights to improve targeted marketing strategies, leading to enhanced customer engagement and increased revenue.

## Stakeholders

- **Marketing Team**
- **Sales Team**

## Calculations

The following calculations were performed using DAX:

- **Recency:** The number of days since the customer's last purchase. This metric helps identify how recently customers have engaged with the brand, which is a strong indicator of their current interest level.
  
- **Frequency:** The total number of purchases made by the customer. This metric is crucial in understanding customer loyalty and engagement. Customers with higher frequency are more likely to be loyal and should be nurtured to maintain their engagement.

- **Monetary Value:** The total amount spent by the customer. This helps identify the most valuable customers based on their spending, allowing for more personalized and high-value offers.

- **RFM Score:** A composite score calculated by ranking each customer on recency, frequency, and monetary value.

- **RFM Segmentation:** Based on RFM score, customers are divided into Champions, Loyal Customers, Potential Loyalists, Promising, New Customers, Need Attention, At Risk, and Lost.

## Insights

### Overall Customer Metrics:
- **Total Customers:** 87,000
- **Average Recency:** 262 days since the last purchase
- **Average Frequency:** 5 purchases per customer
- **Total Monetary Value:** $413M

### Segmentation Breakdown:
- **Potential Loyalists:** 
  - **Percentage of Customers:** 53%
  - **Sales Contribution:** $238M
  - **Characteristics:** These customers have a good frequency and monetary value but may not have the highest recency. They are on the verge of becoming loyal customers and should be targeted with personalized offers and loyalty programs to convert them into long-term customers.

- **Champions:** 
  - **Percentage of Customers:** 10%
  - **Sales Contribution:** $61M
  - **Characteristics:** These are your best customers who have purchased recently, frequently, and have high monetary value. They are highly engaged and should be rewarded with exclusive offers, early access to products, and personalized communications to maintain their loyalty.

- **At Risk:** 
  - **Percentage of Customers:** 9%
  - **Sales Contribution:** $39M
  - **Characteristics:** These customers were once active but have recently shown a decline in engagement. They have a moderate frequency and monetary value but have not purchased recently. Re-engagement strategies, such as special discounts or reminders of their past purchases, can help bring them back.

- **Lost Customers:**
  - **Percentage of Customers:** 2%
  - **Sales Contribution:** $3M
  - **Characteristics:** These customers have not purchased in a long time, have low frequency, and low monetary value. They are unlikely to return without a significant reason. Consider sending a win-back campaign with a strong incentive, or alternatively, consider reallocating marketing efforts to more promising segments.

### Sales by Geography:
  - **USA:** $130M in sales, indicating a strong market presence.
  - **Australia and Canada:** $62M in sales each, showing potential growth opportunities in these regions.

### Top Selling Categories:
- **Electronics:** Highest sales category, suggesting a strong demand and the need for continuous product innovation and competitive pricing.
- **Grocery:** Strong performance, indicating recurring purchases. Focus on maintaining quality and competitive pricing to retain customer loyalty.
- **Clothing:** Significant contributor to sales. Seasonal promotions and trend-based marketing could further boost sales in this category.

## Recommendations

1. **Focus on Potential Loyalists:** With 53% of customers falling into this segment and contributing $238M in sales, this group presents the highest potential for growth. Implement loyalty programs and personalized offers to convert these customers into Champions.

2. **Reward Champions:** Maintain the engagement of your top 10% of customers by offering exclusive deals, early access to new products, and personalized experiences. This will help sustain their loyalty and encourage word-of-mouth marketing.

3. **Re-engage At-Risk Customers:** Develop targeted campaigns to win back the 9% of customers who are at risk of churning. Use data-driven insights to offer them something they cannot resist, such as personalized discounts or reminders of products they previously purchased.

4. **Reconsider Efforts on Lost Customers:** While win-back campaigns can be effective, the low percentage of Lost Customers (2%) and their minimal contribution to sales ($3M) suggest that efforts might be better spent on nurturing higher-value segments. However, a targeted, cost-effective campaign could be employed to test the waters.

5. **Expand in High-Performing Geographies:** The USA is your strongest market, but Australia and Canada also show potential. Consider tailoring marketing strategies specific to these regions to increase market share.

6. **Optimize Product Offerings:** With Electronics, Grocery, and Clothing being top-selling categories, ensure that your inventory, pricing strategies, and marketing campaigns are aligned with customer demand in these areas.
