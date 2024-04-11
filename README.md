# Time Series Forecasting on Energy Consumption using XGBoost Algorithm

### Hourly Energy Consumption

Over 10 years of hourly energy consumption data from PJM in Megawatts

### About Dataset
PJM Hourly Energy Consumption Data
PJM Interconnection LLC (PJM) is a regional transmission organization (RTO) in the United States. It is part of the Eastern Interconnection grid operating an electric transmission system serving all or parts of Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, and the District of Columbia.

The hourly power consumption data comes from PJM's website and are in megawatts (MW).

The regions have changed over the years so data may only appear for certain dates per region.

## To extract as much accuracy as possible, we have used XGBoost-gradient-boosting-decision-tree models.

![Alt text](https://i.postimg.cc/dQm3zGyF/download.png)

### Ideas of what you could do with this dataset:
1. Split the last year into a test set- can you build a model to predict energy consumption?
2. Find trends in energy consumption around hours of the day, holidays, or long term trends?
3. Understand how daily trends change depending of the time of year. Summer trends are very different than winter trends.

### Features:
Time Series Data: Utilizes historical energy consumption data.
XGBoost Model: Implements the XGBoost algorithm for time series forecasting.
Data Preprocessing: Includes data cleaning and feature engineering.
Evaluation Metrics: Analyzes model performance using appropriate metrics.
Visualization: Provides visualizations of predicted vs. actual energy consumption.

### More Dataset 
https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption
