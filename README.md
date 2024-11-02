# Pharmaceutical-Sales-prediction-across-multiple-stores-Project-6
Pharmaceutical Sales prediction  across multiple stores Project-6
Project Overview
This project uses time-series forecasting and regression techniques to predict pharmaceutical sales based on historical sales data across various stores. By accurately forecasting sales, managers can anticipate demand, manage supply chain logistics, and make promotional decisions more effectively.
Key Features:
Predict future sales for multiple stores across different locations.
Account for seasonality, holidays, and promotions.
Generate user-friendly visualizations to showcase predictions and model accuracy.
Dataset
The project uses a dataset containing sales records from various stores, with features like:

Store ID: Unique identifier for each store.
Date: Sales date.
Sales: Sales amount.
Customers: Number of customers.
Promo: Indicator if a store ran a promotion that day.
StateHoliday: Whether the day was a holiday.
Additional features that might impact sales, such as weekends, holidays, and seasonality.
Preprocessing Steps:
Handle missing values.
Feature engineering for variables like weekends, holiday indicators, and promo statuses.
Scale numerical features for model compatibility.
Modeling Approach
Model Choices:
RandomForest Regressor for initial modeling.
Deep Learning (LSTM) for time-series forecasting.
Evaluation Metrics:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Results
The project demonstrates effective sales predictions, achieving an RMSE of approximately [insert value] on the validation dataset. The model accurately captures seasonality and promotional effects.
