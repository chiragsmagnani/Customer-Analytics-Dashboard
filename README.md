# Customer-RFM-Analytics-Dashboard

An interactive RFM (Recency, Frequency, Monetary) analysis dashboard built using Python. This project segments customers based on their transactional behavior, providing actionable insights to improve customer engagement and maximize revenue.

## Executive Summary

Using Python, I built an interactive RFM (Recency, Frequency, and Monetary) analysis dashboard to identify customer segments and analyze purchasing behavior. This project demonstrates the use of data-driven methodologies to visualize customer engagement and prioritize marketing strategies.
The dashboard allows stakeholders to:

1. Quickly identify high-value customers for targeted campaigns.
2. Understand customer retention trends.
3. Enhance decision-making with actionable insights from RFM segmentation.

### Business Problem:

For businesses relying on customer lifetime value, understanding purchasing behavior is crucial. However, the lack of actionable customer segmentation leads to missed marketing opportunities and inefficiencies.

### Key questions addressed include:

1. Who are the most valuable customers?
2. Which customers are at risk of churn?
3. How can targeted marketing strategies improve retention and revenue?

### Methodology:

1. Data Preparation

2. Cleaned and transformed transactional data into an RFM table.

3. Calculated Recency, Frequency, and Monetary values for each customer.

4. Customer Segmentation

5. Assigned R, F, and M scores based on quantile-based ranking.

6. Combined scores to categorize customers into actionable segments (e.g., Champions, At-Risk, 
   Potential Loyalists).
  
7. Visualization:
   Built an interactive  dashboard for real-time exploration of customer segments and patterns.
   Added filters for dynamic exploration (e.g., filter by date range or customer group).

### Skills

Python: Data wrangling (Pandas), visualization (Matplotlib, Seaborn), scoring functions

Data Analysis: Segmentation, quantile ranking, customer behavior analysis

### Results & Business Recommendation:

![Customer-RFM-Analysis](https://github.com/user-attachments/assets/436bec32-326c-4c31-b9e6-7b1ae6c3990f)

The RFM Analytics Dashboard provides a clear and actionable framework for customer segmentation, which can be used by marketing teams to design targeted campaigns.

1. Insights:

   a. Approximately 20% of customers fall under the "Champion" segment, contributing over 50% of 
      total revenue.
  
   b. "At-Risk" customers represent 30% of the base and need engagement strategies to reduce 
       churn.
  
2. Recommendations:

   a. Retention Campaigns: Create targeted email or SMS campaigns for "At-Risk" customers with 
      tailored offers.

   b. Loyalty Programs: Reward "Champions" to increase retention and maximize revenue from the 
      top segment.

   c. Upsell Opportunities: Focus on "Potential Loyalists" with incentives to increase their 
      frequency of purchases.

   These strategies are expected to reduce churn by at least 5% and increase revenue by 
   optimizing customer lifetime value.

### Next Steps:

1. Integrate live transactional data into the dashboard for real-time updates.
2. Automate email campaigns based on customer segmentation.
3. Expand segmentation by incorporating other behavioral metrics, such as time spent on the 
   website.
