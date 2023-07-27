# walmart-forecasting
Demand Forecasting at a store and category level


Business Objective:
The primary objective is to forecast Walmart's unit sales for their retail goods, enabling strategic development, tactical decision-making, and effective management of demand and supply planning. This will help prevent customer service issues and reduce high inventory costs.

Feature Engineering:
To achieve accurate sales forecasting, created various relevant features, including lag sales for different time periods and moving / shifting averages sales representing trends. Additionally, incorporated price-related features such as maximum, minimum, mean, and standard deviation of prices along with normalized prices and price momentum for each product. Calendar-related features, such as weekdays and months, events and holidays were also be integrated.

Model Training:
The approach involves using Python to implement an ensemble of XGBoost, LightGBM, and Exponential Smoothing employing distinct models for different weeks and stores. In total, there will be 30 models—3 states / regions and ten stores—aiming for enhanced forecasting accuracy.

Results:
Achieved a successful sales forecast for 28 days, with a remarkable accuracy level of less than 0.558 WRMSSE (Weighted Root Mean Squared Scaled Error).
