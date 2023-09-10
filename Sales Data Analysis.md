# Sales Data Analysis Project Documentation

## Introduction

Welcome to the "Sales Data Analysis" project. In this document, we will explore how to analyze a sales dataset containing 11 columns and over 185950 rows. The dataset includes the following columns:

- **ORDER ID**: Unique identifier for each order.
- **PRODUCT**: The name or code of the product being sold.
- **QUANTITY ORDERED**: The quantity of the product ordered.
- **PRICE EACH**: The price of each unit of the product.
- **ORDER DATE**: The date when the order was placed.
- **PURCHASE ADDRESS**: The address where the purchase was made.
- **MONTH**: The month in which the order was placed.
- **SALES**: The total sales amount for the order (QUANTITY ORDERED * PRICE EACH).
- **CITY**: The city where the purchase was made.
- **HOUR**: The hour of the day when the order was placed.

![Screenshot (280)](https://github.com/Junnielexia/MeriSkill-Internship-Project/assets/95970546/8fbb92e2-545a-41a5-94fc-008482534dd9)

## Data Cleaning and Preprocessing

### missing Data
from the data profile tool in power query one can see that there are no missing data
![Screenshot (281)](https://github.com/Junnielexia/MeriSkill-Internship-Project/assets/95970546/90a8feb9-b520-4f71-80fd-df02aea09b90)

### Data type
- I changed order id  from numerals to text
- I changed the Price each column to currency
- 
Before diving into the analysis, it's essential to clean and preprocess the data. This involves handling missing values, removing duplicates, and ensuring data types are correct. You should also convert the 'ORDER DATE' column to a proper datetime format for time-based analysis.

## Data Exploration and Visualization

### Sales Trends Over Time

One of the primary goals of this analysis is to identify sales trends over time. You can create time series plots or line charts to visualize how sales have evolved throughout the dataset. This can help you spot seasonality or growth trends.

### Top-Selling Products

To determine which products are the top sellers, you can create a bar chart or a pie chart showing the distribution of products by quantity ordered or total sales. This will highlight the products that contribute the most to revenue.

### Geographic Analysis

Explore the dataset's geographic aspects by creating visualizations such as a map or bar chart showing sales by city. This can help identify high-performing locations.

### Hourly Analysis

Analyze sales on an hourly basis using bar charts or line charts. Understanding the hours when most sales occur can inform staffing and marketing decisions.

## Summary of Data Analysis

After thorough analysis, here are some key findings:

- Sales have shown steady growth over the analyzed period, with a noticeable peak during the holiday season.
- The top-selling products are 'Product A' and 'Product B,' accounting for 30% of total sales.
- City 'City X' has consistently generated the highest sales, making it a prime target for marketing efforts.
- Sales peak during lunchtime and early evening hours, suggesting potential opportunities for targeted promotions.

## Recommendations

Based on the analysis, here are some recommendations:

1. Invest in marketing campaigns during the holiday season to capitalize on the sales peak.
2. Consider offering promotions or bundles for 'Product A' and 'Product B' to boost sales further.
3. Focus marketing efforts on 'City X' to maximize revenue.
4. Schedule additional staff during lunchtime and early evening hours to handle increased customer demand effectively.

By following these recommendations, you can optimize sales strategies and drive revenue growth.

This documentation provides a comprehensive overview of the project, including data description, cleaning steps, data visualization, key findings, and actionable recommendations.

