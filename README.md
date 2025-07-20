**📊 Time Series Analysis Project**
This project explores time series analysis techniques using two separate datasets:

**🔹 Time_Series_1: Google Trends Analysis**
This notebook analyzes monthly Google Trends data for the search terms "Diet", "Gym", and "Finance" to uncover patterns in public interest.

**Key Steps:**
Data Preparation: Converts the 'Month' column to datetime format and sets it as the index.

Visualization: Plots trends, rolling means, and seasonal patterns for each search term.

Modeling: Applies ARIMA and SARIMAX models to understand components and forecast trends.

Diagnostics: Uses Autocorrelation (ACF) and Partial Autocorrelation (PACF) plots to guide model selection.

Objective: Identify historical trends and develop insights for future forecasting.

**🔹 Time_Series_2: PJME Energy Consumption EDA**
This notebook performs an exploratory data analysis on the PJME hourly energy consumption dataset.

**Key Steps:**
Data Loading & Cleaning: Reads the dataset, converts the 'Datetime' column, and sets it as the index.

Visualization: Plots overall consumption trends and seasonal variations (daily, weekly, monthly).

Feature Engineering: Extracts time-based features like year, month, day, hour, etc.

Outlier Detection: Uses boxplots to spot irregular consumption values.

Time Series Decomposition: Breaks down the data into trend, seasonal, and residual components using both additive and multiplicative models.

Insights: Draws conclusions on consumption behavior and seasonality.

**📌 Purpose**
This project demonstrates how to work with time series data through:

Trend and seasonality detection

Forecasting preparation

Exploratory time-based feature extraction

It serves as a foundation for deeper forecasting models and energy/data consumption predictions.
