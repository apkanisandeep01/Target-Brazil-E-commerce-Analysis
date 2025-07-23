# Target Brazil E-commerce Analysis

[cite_start]This repository contains a business case analysis for Target's e-commerce operations in Brazil, focusing on 100,000 orders placed between 2016 and 2018[cite: 7]. [cite_start]The analysis aims to extract valuable insights and provide actionable recommendations based on a comprehensive dataset[cite: 8, 60].

## Project Overview

[cite_start]The project involves analyzing various dimensions of customer orders, including order status, price, payment and freight performance, customer location, product attributes, and customer reviews[cite: 7, 9]. The insights derived aim to help Target optimize its operations in the Brazilian market.

## Dataset

[cite_start]The analysis is based on 8 interconnected CSV files[cite: 10], providing a comprehensive view of orders, customers, sellers, products, payments, reviews, and geolocation data.

* [cite_start]`customers.csv` [cite: 11]
* [cite_start]`sellers.csv` [cite: 12]
* [cite_start]`order_items.csv` [cite: 13]
* [cite_start]`geolocation.csv` [cite: 14]
* [cite_start]`payments.csv` [cite: 15]
* [cite_start]`reviews.csv` [cite: 16]
* [cite_start]`orders.csv` [cite: 17]
* [cite_start]`products.csv` [cite: 18]

## Key Findings & Insights

* [cite_start]**Significant Order Growth**: There is an increasing trend in the number of orders placed year by year[cite: 94]. [cite_start]Orders grew from 329 in 2016 to 45,101 in 2017, and further to 54,011 in 2018[cite: 91, 95].
* [cite_start]**No Clear Monthly Seasonality**: Comparing the month-on-month data across the three years, no specific seasonality trend was observed[cite: 135].
* [cite_start]**Peak Order Time**: Brazilian customers mostly place their orders during the **Afternoon** (13:00 - 18:00)[cite: 159, 149].
* [cite_start]**Customer Reach**: The dataset includes purchase history from customers across 4,119 cities and 27 states in Brazil[cite: 82].
* [cite_start]**Order Cost Increase**: The cost of orders increased by approximately **173.005%** from 2017 to 2018, specifically for months between January and August[cite: 208, 209].
* **Freight & Delivery Performance**:
    * [cite_start]**Highest Average Freight**: States like RR, PB, RO, AC, and PI have the highest average freight values[cite: 276].
    * [cite_start]**Lowest Average Freight**: States like SP, PR, MG, RJ, and DF have the lowest average freight values[cite: 287].
    * [cite_start]**Fastest Delivery (vs. Estimated)**: States such as AL, MA, SE, ES, and BA received ordered products earlier compared to their estimated delivery dates[cite: 322, 324].
* [cite_start]**Payment Trends**: The analysis shows the number of orders placed month-wise using different payment types like credit card, UPI, debit card, etc.[cite: 338]. [cite_start]It also indicates the total number of customers who opted to pay in monthly installments (EMI)[cite: 347].

## Technologies Used

* **SQL**: Used for data extraction, transformation, and analysis.

## How to Use

To replicate this analysis:

1.  Clone this repository.
2.  Load the provided CSV files into your preferred SQL database.
3.  Execute the SQL queries (as detailed in the full analysis document) to generate insights.

## Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests.
