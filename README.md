# US-House-Price-Data-Science-Project

## US Home Prices Analysis
### Introduction
This project aims to analyze and understand the key factors influencing US home prices over the last 20 years (2004-2024). By collecting and examining various economic and demographic indicators, we seek to uncover insights that can provide valuable information for stakeholders in the real estate market.
##### The data of the factors which influences the home prices such as Per Capita GDP, Consumer Price Index (CPI), Construction Material Costs, Median Household Income, Subsidies, Unemployment Rate, working population, etc are collected from FRED Website.

##### The S&P Case-Schiller Home Price Index (CS_Index) is used as a proxy for home prices. The Data files are sourced from the Federal Reserve Economic Data (FRED) website.

## Step-by-Step Plan

### Define the Problem:
To Understand how different factors such as GDP, unemployment rate, interest rates, and population dynamics affect home prices in the US.

### Data Collection: 
Gathered data from reliable sources such as Federal Reserve Economic Data (FRED), government agencies, and real estate platforms.

### Data Preprocessing: 
Cleaned the data by handling missing values, converting data types, and standardizing.

### Exploratory Data Analysis (EDA): 
Explored the data using various visualizations to understand trends, correlations, and distributions.

### Feature Engineering: 
Created new features that may have an impact on home prices, such as lagged variables or rolling averages.

### Model Building: 
Constructed predictive models such as Linear Regression, Random Forest, Gradient Boosting Machines, etc to analyze the relationship between factors and home prices.

### Model Evaluation: 
Evaluate the models using metrics like R² and RMSE  to understand their predictive performance.

### Interpretation: 
Interpreted the model results to identify the most significant factors influencing home prices and provide actionable insights.

### Interactive Visualizations: 
Used Plotly to create interactive plots.

### Results:
The Best Performing model was GradientBoostingRegressor() with R2 Score: 0.9978464577980202 and RMSE: 0.04095546385887566
The most important factors affecting the US House Price are - cost of material, Subsidy, Median Household Income, CPI, GDP, Unemployment Rate and Working Population.

#### The Files named US_HousePrice_Part1.ipynb Contains the Data Preparation part and US_HousePrice_Part2.ipynb contains the Model Building Part.

### References:
https://fred.stlouisfed.org/  
https://www.investopedia.com/articles/mortgages-real-estate/10/understanding-case-shiller-index.asp


