# Wallmart-Project
Predicting the weekly sales of each store for 12 weeks

# 1. Problem Statement: Walmart Sales Forecasting and Analysis
Walmart operates a vast network of retail stores across various locations, and its sales performance is influenced by multiple factors, including seasonality, economic indicators, and promotional events. Analyzing and predicting sales trends is crucial for optimizing inventory management, staffing, and marketing strategies.

# 2. The objective of this project is to analyze historical sales data from Walmart stores to:
# Identify Key Sales Drivers – Understand the impact of factors like holidays, promotions, consumer price index (CPI), unemployment rate, fuel prices, and temperature on weekly sales.
# Detect Seasonality and Trends – Explore patterns in sales data to determine high and low sales periods.
# Performance based on Temperature - Does temperature affect the weekly sales in any manner
# Evaluate Store Performance – Identify the best and worst-performing stores based on historical data and analyze the reasons behind performance variations.
# Predict Future Sales – Develop predictive models using machine learning techniques to forecast sales for the upcoming weeks and assist in decision-making.

# 3. Data Description
# I. Dataset Overview:
Total Rows: 6,435
Total Columns: 8

# II. Column Details:
# Store (int64): Store ID (1 to 45)
# Date (object): Weekly timestamp (Format: DD-MM-YYYY)
# Weekly_Sales (float64): Total sales for the store in that week
# Holiday_Flag (int64): Indicates if the week had a holiday (1 = Holiday, 0 = Non-Holiday)
# Temperature (float64): Average temperature for that week
# Fuel_Price (float64): Fuel price for that week
# CPI (float64): Consumer Price Index
# Unemployment (float64): Unemployment rate for that period

**4. Data Pre-processing Steps and Inspiration**
1. Load the Data
2. Cheking the information of the data such as datatype of the column, number of columns and rows
3. Handling missing values
4. Handling duplicated values
5. Checking the unique values
6. Plotting the outliers with the help of boxplot
7. Converting the datatype of Date column from object to Datetime
