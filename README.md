# Project 1 : Customer Segmentation Analysis

## Introduction

This project is centered around customer segmentation, an essential strategy in modern marketing and business analytics. The goal is to analyze customer data to identify distinct segments within the customer base, enabling targeted marketing strategies, improved customer satisfaction, and optimized resource allocation.

### Objectives:
- **Identify key customer segments** based on purchasing behavior and demographic information.
- **Analyze the characteristics** of each segment to understand their preferences and needs.
- **Provide actionable insights** for targeted marketing and business decisions.

## Data Insights

### Dataset Overview:
The dataset contains various features related to customer demographics, purchase history, and response to marketing campaigns. Key columns include:
- **Income**: The annual income of customers.
- **Kidhome**: The number of children in the household.
- **Teenhome**: The number of teenagers in the household.
- **Recency**: Days since the last purchase.
- **MntWines**: Amount spent on wine products.
- **MntFruits**: Amount spent on fruit products.
- **MntMeatProducts**: Amount spent on meat products.
- **MntFishProducts**: Amount spent on fish products.
- **MntSweetProducts**: Amount spent on sweet products.
- **MntGoldProds**: Amount spent on gold products.
- **AcceptedCmpOverall**: Number of accepted marketing campaigns.

### Analysis and Insights:
- **Customer Segments**: The analysis likely includes clustering techniques to identify distinct customer segments. Each segment can be characterized by unique spending behaviors and demographic factors.
- **Spending Patterns**: By analyzing the total spending (`MntTotal`) and spending on regular products (`MntRegularProds`), we can identify high-value customers who contribute significantly to revenue.
- **Campaign Effectiveness**: The `AcceptedCmpOverall` feature allows for the evaluation of the effectiveness of past marketing campaigns, helping in the design of future strategies.

## Conclusion

This project offers a comprehensive look at customer segmentation, providing valuable insights into customer behavior and preferences. These insights can drive targeted marketing efforts, enhance customer satisfaction, and ultimately lead to increased business success.

----------------------------------------------------------------------------------------------------------------------------------------------------------------


# Project 2 : House Prices Analysis

## Project Overview
This project analyzes a housing dataset to uncover factors that influence house prices. It involves data preprocessing, exploratory data analysis, and predictive modeling using linear regression.

## Dataset
The dataset contains the following features related to houses:

- **price**: The selling price of the house.
- **area**: The size of the house in square feet.
- **bedrooms**: The number of bedrooms.
- **bathrooms**: The number of bathrooms.
- **stories**: The number of stories in the house.
- **mainroad**: Whether the house is located on the main road (`yes`/`no`).
- **guestroom**: Presence of a guest room (`yes`/`no`).
- **basement**: Presence of a basement (`yes`/`no`).
- **hotwaterheating**: Whether the house has hot water heating (`yes`/`no`).
- **airconditioning**: Whether the house has air conditioning (`yes`/`no`).
- **parking**: The number of parking spaces.
- **prefarea**: Whether the house is in a preferred area (`yes`/`no`).
- **furnishingstatus**: The furnishing status of the house (`furnished`, `semi-furnished`, `unfurnished`).

## Dependencies
The project requires the following Python libraries:
- **Python 3.x**
- **Pandas**: `pip install pandas`
- **NumPy**: `pip install numpy`
- **Matplotlib**: `pip install matplotlib`
- **Scikit-learn**: `pip install scikit-learn`

## Data Insights
Key insights obtained from the dataset include:
- **Price Distribution**: Analysis of how house prices are distributed.
- **Feature Relationships**: Investigation of correlations between house features and prices.
- **Predictive Modeling**: A linear regression model to predict house prices based on various features, evaluated using metrics like mean squared error.
