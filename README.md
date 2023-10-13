# FoodHub Data Analysis

This repository contains the code and analysis for the data analysis project for FoodHub, a food aggregator company. The objective of this project is to analyze the data of different orders made by registered customers in order to gain insights and improve the company's business.

## Objective

The objective of this project is to answer key questions provided by the Data Science team at FoodHub. By analyzing the data, we aim to gain a fair idea about the demand of different restaurants, which will help in enhancing the customer experience and improving the business.

## Data Description

The data provided for this analysis contains various attributes related to a food order. The data dictionary for the attributes is as follows:

- `order_id`: Unique ID of the order
- `customer_id`: ID of the customer who ordered the food
- `restaurant_name`: Name of the restaurant
- `cuisine_type`: Cuisine ordered by the customer
- `cost`: Cost of the order
- `day_of_the_week`: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
- `rating`: Rating given by the customer out of 5
- `food_preparation_time`: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
- `delivery_time`: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information.

## Analysis

The analysis code and results can be found in the Jupyter Notebook file `foodhub_data_analysis.ipynb`. The notebook contains step-by-step analysis of the data, including data cleaning, exploratory data analysis, and answering the key questions provided by the Data Science team.

## Key Questions

The key questions that will be answered through this analysis include:

1. What are the most popular cuisines among FoodHub customers?
2. Which restaurants have the highest ratings?
3. Is there a correlation between food preparation time and customer ratings?
4. How does the delivery time vary on weekdays and weekends?
5. What is the average cost of orders from different restaurants?

## Conclusion

By analyzing the data, we will be able to provide insights and answers to the key questions, which will help FoodHub in improving their customer experience and enhancing their business. The analysis code and results can be found in the Jupyter Notebook file `foodhub_data_analysis.ipyn
