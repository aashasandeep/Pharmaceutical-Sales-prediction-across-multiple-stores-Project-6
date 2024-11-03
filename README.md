![Total sales bar plot](https://github.com/user-attachments/assets/1b2c406d-efeb-4646-8a73-cc6b849e7f80)
![time series](https://github.com/user-attachments/assets/073fc766-3018-46e8-8417-ebedc2c106ac)
![time series ](https://github.com/user-attachments/assets/4b8fadc5-d1c4-42cd-a0bb-bd82dbaf4e0a)
![storewise promo effect on sales](https://github.com/user-attachments/assets/af16839a-c7f3-4dc7-8c1d-19cd96c20aed)
![Scatter plot of -6](https://github.com/user-attachments/assets/f2645edf-ad5f-4da7-a6b8-ad359a6d8024)
![sale per customer trend proj-6](https://github.com/user-attachments/assets/8584cfae-889c-4850-9e88-f6c605b3a2c5)
![promo and sales sum ](https://github.com/user-attachments/assets/097245fb-1751-4681-b2e0-93f8fb2c4495)
![promo and customers](https://github.com/user-attachments/assets/9a9f0685-2c79-4d28-91dc-4245702f0b14)
![proj-6](https://github.com/user-attachments/assets/2270fa9d-798a-40b6-9865-8c95991acd1e)
![proj-6 store type](https://github.com/user-attachments/assets/ea08ae53-6383-4d6a-897d-2fa3ebbacfa3)
![pro-6 Heat map](https://github.com/user-attachments/assets/33a6f0df-1d02-46bd-98be-14f0265df705)
![number of holidays and stateholidays](https://github.com/user-attachments/assets/65a848e7-9ed1-4a24-829d-f800a765760e)
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
Task 1 - Exploration of customer purchasing behaviour,1.2 - Logging,Task 2 - Prediction of store sales ,2.1 Preprocessing,2.2 Building models with sklearn pipelines,2.3 Choose a loss function,2.4 Post Prediction analysis,2.5 Serialize models,2.7 Using MLFlow to serve the prediction,Task 3 - Serving predictions on a web interface,ask 1 - Exploration of customer purchasing behaviour
Results
The project demonstrates effective sales predictions, achieving an RMSE of approximately [insert value] on the validation dataset. The model accurately captures seasonality and promotional effects.
Precise sales prediction is an essential and inexpensive way for each company to augment their profits, decrease their costs, and achieve greater flexibility to changes. In other words, exact sales forecasting is utilized for capturing the tradeoff between customer demand satisfaction and inventory costs. Especially, for the pharmaceutical industry, successful sales forecasting systems can be very beneficial, due to the short shelf-life of many pharmaceutical products and the importance of the product quality which is closely related to the human health.

In this project, we will forecast the sales of different stores for six weeks.
