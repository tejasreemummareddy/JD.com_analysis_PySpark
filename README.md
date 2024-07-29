# Analysis of JD.com Transactional Data

## Executive Summary
The rise of e-commerce has introduced new challenges at both strategic and operational levels. This project analyzes JD.com's transactional data to understand user behavior and order trends, aiming to provide actionable insights for marketing and customer interaction improvements. Utilizing PySpark for data processing, we examined user demographics and purchase patterns. Our analysis highlighted critical factors such as user level and purchasing power in predicting consumer behavior. JD.com can leverage these insights to refine pricing and promotional strategies, enhancing customer satisfaction and strengthening its market position.

## Problem Statement
JD.com faces intense competition in the e-commerce industry, necessitating a deeper understanding of consumer behavior to enhance its marketing strategies. This project addresses the challenge of retaining customers and increasing sales amidst changing consumer preferences. By analyzing user demographics, interactions, and responses to pricing tactics, JD.com can better target its marketing efforts and optimize resource allocation.

## Analysis

### Data Description
We used two primary datasets: User Data (demographics and socioeconomic characteristics) and Order Data (transaction details). Key findings include:

- **User Data**: Contains demographic information such as age, gender, marital status, education, city level, and purchase power.
- **Order Data**: Details transactions, including order date, quantity, pricing, and various discount types.

### Data Preparation
- **Data Cleaning and Preprocessing**: Addressed missing and undefined values, handled outliers, and ensured data integrity.
- **Data Integration**: Merged User and Order datasets on user_ID, creating a comprehensive dataset for analysis.

### Visualization and Insights
- **Demographic Distribution**: Bar charts displaying age, gender, and marital status distributions.
- **Purchase Trends**: Pivot tables and line charts showing new user acquisitions and purchase activity by age and education level.
- **Top Customers and Products**: Charts identifying top spenders and frequently purchased products.

### Model Evaluation
- **Logistic Regression**: Achieved 61.63% accuracy in predicting purchase likelihood.
- **Random Forest**: Slightly lower accuracy at 56.28%, suggesting potential for further tuning and optimization.

## Business Suggestions

### Strengthen Loyalty Initiatives
Enhance loyalty programs with personalized offers, tier-based rewards, and exclusive promotions to increase engagement and purchases.

### Focused Marketing for Plus Members
Develop targeted campaigns to convert regular customers into Plus members, emphasizing the benefits and exclusive offers available to them.

### Customize Marketing Based on Purchase Power
Tailor marketing strategies according to the purchasing power of users, focusing on premium products for high-value customers and discounts for those with lower purchasing power.

### Data-Driven Inventory Management
Optimize inventory levels based on product popularity insights, maintaining higher stock of best-sellers and reducing less popular items to save costs and boost sales.

### Improve Client Segmentation
Utilize data analytics to enhance consumer segmentation, enabling more effective and customized marketing campaigns and product recommendations.

### Customer Retention Strategies
Implement retention plans based on identified key characteristics, such as referral programs, feedback loops, and loyalty rewards to reduce churn and increase customer lifetime value.

## Conclusion
This project provides valuable insights into JD.com's consumer behavior, highlighting the importance of user level, purchase power, and Plus membership in influencing purchase decisions. By focusing on loyalty programs, targeted marketing, and data-driven strategies, JD.com can enhance customer satisfaction, increase retention, and optimize marketing efforts, ultimately driving long-term success.
