# Superstore Customer Segmentation RFM Analysis
## Context
In a highly competitive retail environment, understanding customer purchasing behavior is critical for driving business growth. However, without a structured approach to customer segmentation, businesses struggle to identify high-value customers, optimize marketing strategies, and improve customer retention.

## Objective
This analysis applies Recency, Frequency, and Monetary (RFM) segmentation to the Superstore dataset to categorize customers into distinct clusters. By leveraging these insights, we aim to:
* Identify high-value customers for targeted marketing efforts.
* Detect at-risk customers to improve retention strategies.

### Notes
* Recency: How recently has the customer made a purchase
* Frequency: How frequent is the customer in buying
* Monetary: How much does the customer spend

## Conclusion

*see analysis notebook for details*

Customers can be segmented into 4 groups based on their purchase behaviour. 
* Churned Customers - who has not made a purchase in ~290 days, low frequency buyers, low monetary value
* Churning Customers - who has not made a purchase in ~220 days, high frequency buyers, medium monetary value
* Top Customers / Recent Frequent buyers with large basket size
* New Customers / Recent Frequent buyers with medium basket size

## Strategic Recommendation

*see analysis notebook for details*

### 1. Churned Customers
**Goal: Reactivate these customers and bring them back to purchasing.**

* Re-engagement Campaigns: Send personalized emails with exclusive offers (e.g., "We Miss You! Enjoy 20% Off Your Next Purchase").
* Win-Back Discounts: Provide targeted discounts for previous purchases or related products.
* Survey & Feedback Collection: Understand why they stopped buying through a quick survey in exchange for a small incentive.
* Retargeting Ads: Use digital ads to remind them of past purchases or showcase new arrivals.
* Subscription/Loyalty Program Promotions: Encourage them to re-engage with a small reward or free trial offer.

### 2. Churning Customers
**Goal: Prevent churn and increase engagement before they leave.**

* Exclusive VIP Offers: Offer loyalty perks like early access to sales or free shipping.
* Personalized Product Recommendations: Use past purchase data to recommend related or complementary items.
* Limited-Time Offers: Provide time-sensitive discounts or bundle deals to create urgency.
* Engagement Reminders: Send reminders like “You’ve Loved These Before – Ready for More?” with past purchase history.
* Loyalty Program Optimization: Reward repeat purchases or offer a bonus if they return within a certain timeframe.
  
### 3. Recent Frequent Buyers (Large Basket Size)
**Goal: Retain and increase customer lifetime value (CLV).**
* Premium Membership Upsell: Offer free shipping, exclusive discounts, or subscription services.
* Cross-Selling & Bundling: Recommend high-value add-ons and complementary products.
* Personalized Rewards: Provide tiered incentives (e.g., “Spend $X more for an extra discount”).
* Early Access to New Products: Make them feel valued by giving early access to new collections.
* Referral Program: Encourage them to bring friends with incentives like discounts for both referrer and referee.
  
### 4. Recent Frequent Buyers (Small Basket Size)
**Goal: Encourage higher spend per transaction.**
* Upsell Higher-Ticket Items: Highlight premium versions of products they typically buy.
* Bundle & Volume Discounts: Offer “Buy More, Save More” deals to encourage larger basket sizes.
* Subscription Options: If applicable, introduce subscription models for frequently purchased items.
* Loyalty Program Enrollment: Encourage repeat purchases by providing points for larger purchases.
* A/B Testing Promotions: Test different price-based incentives to see which increases order size.
