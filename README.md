# Time-Series
Time_Series_1 notebook performs a time series analysis on Google Trends data for the search terms 'Diet', 'Gym', and 'Finance'. The analysis includes:

Loading and preparing the data, including converting the 'Month' column to datetime objects and setting it as the index.
Visualizing the trends and seasonality of each search term using plots and rolling means.
Applying ARIMA and SARIMAX models to understand the time series components and prepare for potential forecasting.
Analyzing the autocorrelation (ACF) and partial autocorrelation (PACF) plots to help identify appropriate model parameters.
The overall goal is to understand the historical patterns and potentially forecast future search interest for these topics.

Time_Series_2 notebook performs an exploratory data analysis on the PJME hourly energy consumption dataset.

 The analysis includes:

Loading Libraries and Data: Essential libraries like pandas, numpy, matplotlib, and seaborn are imported, and the dataset is loaded into a pandas DataFrame.
Data Inspection and Cleaning: The data types are checked, and the 'Datetime' column is converted to the correct datetime format. The 'Datetime' column is then set as the index for easier time series analysis.
Time Series Plot: An initial plot of the energy consumption over time is generated to visualize the overall trend and patterns.
Feature Engineering: New features like year, month, week, day, hour, day of the week (string and numerical), and year-month are extracted from the 'Datetime' index.
Seasonal Plots: Plots are generated to analyze the seasonality of energy consumption at monthly, weekly, and daily levels.
Outlier Detection: A boxplot is used to visualize the distribution of energy consumption and identify potential outliers.
Time Series Decomposition: The time series data is decomposed into its trend, seasonal, and residual components using both additive and multiplicative models to better understand the underlying patterns.
Conclusions: Based on the visualizations, conclusions are drawn about the trends, seasonality, and outliers in the energy consumption data.
Time_Series_2 provides a good starting point for understanding the characteristics of the PJME hourly energy consumption data before proceeding to more advanced time series analysis or modeling.
