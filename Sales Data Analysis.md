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
Before diving into the analysis, it's essential to clean and preprocess the data. This involves handling missing values, removing duplicates, and ensuring data types are correct.

### missing Data

From the data profile tool in power query one can see that there are no missing data

![Screenshot (281)](https://github.com/Junnielexia/MeriSkill-Internship-Project/assets/95970546/90a8feb9-b520-4f71-80fd-df02aea09b90)

### Data type
- I changed order id  from numerals to text
- I changed the Price each column to currency
- I Changed Order date from date time to shortdate
- I created a revenue column to get the actual payment made from the quantity of product sold.
- I changed Hours n month column from text to whole numbers.
  

![Screenshot (282)](https://github.com/Junnielexia/MeriSkill-Internship-Project/assets/95970546/8125ea35-ffb2-4529-baa1-9905466a6c06)


## Data Exploration and Visualization

### Sales Trends Over Time

I created time series plots to visualize how sales have evolved throughout the dataset. This can help you spot seasonality or growth trends. I noticed two peaks from March through JULY and October to December which is the biggest sales month.

### Top-Selling Products

To determine which products are the top sellers, I created chart showing the distribution of products by quantity ordered or total sales. This will highlight the products that contribute the most to revenue. By quantity Ordered we have AAA Batteries,AA Batteries,USB-c chargers were the top 3 products and by revenue generated Macbook, iPhone, Thinkpad were the top 3 products.

### Geographic Analysis

From the analysis I was able to identify high-performing locations such as San Francisco, Los Angeles, New York, Boston, Atalanta. 

### Hourly Analysis

Understanding the hours when most sales occur can inform staffing and marketing decisions. From the dataset we were able to recognize sale peaks from 8am to 8am. 

## Summary of Data Analysis

![Screenshot (284)](https://github.com/Junnielexia/MeriSkill-Internship-Project/assets/95970546/a862461b-cb2b-4632-9b71-92348a609052)

# SALES DASHBOARD

![Screenshot (285)](https://github.com/Junnielexia/MeriSkill-Internship-Project/assets/95970546/692673ad-7ec0-4991-9dc0-c364884ffded)

# Product Analzsis

![Screenshot (286)](https://github.com/Junnielexia/MeriSkill-Internship-Project/assets/95970546/eeed2516-0995-41b9-b743-f2eec4c55b63)

After thorough analysis, here are some key findings:

- Sales have shown steady growth over the analyzed period, with a noticeable peak during the holiday season.
- The top-selling products are 'Macbook' and 'iPhone,' accounting for 30% of total sales.
- City 'San Francisco' has consistently generated the highest sales, making it a prime target for marketing efforts.
- Sales peak during lunchtime and early evening hours, suggesting potential opportunities for targeted promotions.

## Recommendations

Based on the analysis, here are some recommendations:

1. Invest in marketing campaigns during the holiday season to capitalize on the sales peak.
2. Consider offering promotions or bundles for 'LG Washing Machine' and 'LG Dryer' to boost sales further.
3. Focus marketing efforts on Austin and Portland to maximize revenue.
4. Schedule additional staff during lunchtime and early evening hours to handle increased customer demand effectively.

By following these recommendations, you can optimize sales strategies and drive revenue growth.

This documentation provides a comprehensive overview of the project, including data description, cleaning steps, data visualization, key findings, and actionable recommendations.

