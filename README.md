## Target Brazil Order Analysis
This repository contains a data analysis project focused on Target's e-commerce operations in Brazil, utilizing a dataset of 100,000 orders placed between 2016 and 2018. The goal of this analysis is to extract key business insights and provide actionable recommendations.

##  Project Overview
The project involves analyzing various aspects of customer orders, including sales trends, customer demographics, payment methods, shipping efficiency, and delivery performance. The insights derived aim to help Target optimize its operations in the Brazilian market.

## Dataset
The analysis is based on 8 interconnected CSV files, providing a comprehensive view of orders, customers, sellers, products, payments, reviews, and geolocation data.
- customers.csv
- sellers.csv
- order_items.csv
- geolocation.csv
- payments.csv
- reviews.csv
- orders.csv
- products.csv
  
##  Key Findings & Insights
Significant Order Growth: Orders showed a strong increasing trend from 2016 (329 orders) to 2017 (45,101 orders) and 2018 (54,011 orders).
No Clear Monthly Seasonality: While annual growth is evident, month-on-month analysis did not reveal a consistent seasonal pattern across the years.
Peak Order Time: Brazilian customers most frequently place orders during the Afternoon (13:00 - 18:00).
Customer Reach: Orders originated from 4,119 distinct cities and 27 states in Brazil.
Order Cost Increase: A substantial 173% increase in order cost was observed between Jan-Aug 2017 and Jan-Aug 2018.
## Freight & Delivery Performance:
Highest Average Freight: States like RR, PB, RO experienced the highest average freight charges.
Lowest Average Freight: States like SP, PR, MG had the lowest average freight charges.
Fastest Delivery (vs. Estimated): States such as AL, MA, SE, ES, and BA showed deliveries significantly faster than estimated.
Payment Trends: Credit card is a dominant payment type. A large number of customers opt for single-installment payments, though multi-installment options are also utilized.

## Technologies Used
SQL: For data extraction, transformation, and analysis.

## How to Use
To replicate this analysis:

## Clone this repository.
Load the provided CSV files into your preferred SQL database.
Execute the SQL queries (as detailed in the full analysis document) to generate insights.

## Contributing
Contributions are welcome! Please feel free to open issues or submit pull requests.
