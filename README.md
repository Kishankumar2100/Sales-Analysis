# Sales-Analysis

This project aims to analyze sales data to extract meaningful insights. The analysis includes determining the best month for sales, identifying the city with the highest sales, understanding the optimal times for advertisements, and identifying the most sold products and product combinations.

## Table of Contents
1. [Project Overview]
2. [Data Preparation]
3. [Data Cleaning]
4. [Analysis]
    - [Best Month for Sales])
    - [City with Highest Sales]
    - [Optimal Advertisement Time]
    - [Most Sold Products]
    - [Products Sold Together]
5. [Conclusion]

## Project Overview

This project involves:
- Merging multiple sales data files into a single CSV file.
- Cleaning and preparing the data for analysis.
- Performing various analyses to answer specific business questions.



## Data Cleaning
The data is cleaned to ensure accuracy and consistency:

- Drop rows with NaN values.
- Remove rows with irrelevant data.
- Convert columns to the correct data types.

## Analysis

### Best Month for Sales
To determine the best month for sales, the following analysis is performed:

1. Calculate sales by multiplying the quantity ordered by the price each.
2. Group the data by month and sum the sales.
3. Plot a bar chart of sales per month.

**Result:** December is the best month for sales with a total of $4,613,443.34.

### City with Highest Sales
To identify the city with the highest sales, a city column is added:

1. Extract the city and state from the purchase address.
2. Combine the city and state into a single column.
3. Plot a bar chart of sales per city.

### Optimal Advertisement Time
To find the best time to display advertisements:

1. Convert the order date to datetime format.
2. Extract the hour and minute from the order date.
3. Plot a line graph of the number of orders per hour.

**Recommendation:** Advertisements should be displayed slightly before 11 AM or 7 PM.

### Most Sold Products
To determine the most sold products:

1. Group the data by product and sum the quantity ordered.
2. Plot a bar chart of the quantity ordered per product.

**Result:** AAA Batteries are the most sold product.

### Products Sold Together
To identify products that are often sold together:

1. Find duplicated order IDs.
2. Group the products by order ID and combine them into a single column.
3. Count the most common product combinations.

## Conclusion
This project provides insights into the sales data, including the best month for sales, the city with the highest sales, optimal advertisement times, and the most sold products and product combinations. These insights can help in making informed business decisions.
