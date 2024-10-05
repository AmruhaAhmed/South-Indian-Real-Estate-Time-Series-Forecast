# South Indian Real Estate Time Series Forecast
![image](https://github.com/user-attachments/assets/9e6ea9c7-e7ee-4ab4-8a82-89d6f31df605)

This project aims to give insights as well as forecast real estate prices in South Indian cities of Bangalore, Hyderabad, and Chennai. By employing time series forecasting techniques using ARIMA model, 
the project analyzes historical real estate data to make accurate predictions regarding price trends in 2025. The goal is to provide valuable insights into the prevailing trends in the real estate market, 
also helping stakeholders make informed decisions based on projected price movements.

## Features

This project encompasses a variety of key features, including:

1. Data Preprocessing: 
A rigorous data cleaning process is employed to ensure the dataset is suitable for analysis. This includes identifying and addressing missing values and formatting dates appropriately.

2. City-Specific Modeling:
 The project implements separate forecasting models for each of the three cities—Bangalore, Hyderabad, and Chennai. This city-specific approach allows for a more nuanced understanding of regional real estate dynamics and price behavior.

3. ARIMA Forecasting: 
The ARIMA model, known for its effectiveness in time series forecasting, is utilized to predict future real estate prices. The model’s parameters are optimized to ensure the best fit for the historical data, enhancing the reliability of the forecasts.

4. Real Estate Dashboard:
The project implements a real estate dashboard that gives insights into the prevailing trends in each of the three cities . It incorporates interactive visuals and filters the data according to filters such as city, price, locality and area.

## Methodology

The methodology employed in this project includes several critical steps:

1. Data Cleaning:
The initial stage involves loading the dataset and conducting thorough cleaning. This includes checking for and handling missing values, converting text formats into a  consistent format, and extracting Locality of the house through Property Title.  The objective is to ensure that the dataset is as accurate and comprehensive as possible.

2. Real Estate Dashboard:

A dashboard is made to visualize the clean and accurate data that gives insights into the prevailing market trends. Appropriate filters are added to gain a deeper understanding of the data.


3. Model Development: 
Following data cleaning, the ARIMA model is developed. Auto ARIMA is utilized to streamline the process of selecting the best parameters for the model. This automated approach saves time and ensures that the model configuration is optimal for the given dataset. Once the model is trained on the cleaned data, predictions are generated for future time periods.

4. Forecast Evaluation: 
After generating forecasts, the results are evaluated using performance metrics such as MAE, RMSE, R², AIC and BIC . These metrics provide a quantitative measure of the model’s predictive power and help assess how closely the forecasts align with actual historical data.

5. Visualization: 
The project includes various visualizations to illustrate the data trends and the model's forecasts. These visualizations play a crucial role in communicating the results and findings of the analysis to stakeholders. They depict historical prices, forecasted values, and confidence intervals, offering a comprehensive view of the projected real estate market.

## Model Evaluation

In the forecast of price trends in the year 2025 in the city of Hyderabad, 8 ARIMA models were developed and the metrics were obtained as follows:
![image](https://github.com/user-attachments/assets/ad19b767-7fba-4688-9dc7-a8ebb545d265)


In the forecast of price trends in the year 2025 in the city of Bangalore, 8 ARIMA models were developed and the metrics were obtained as follows:
![image](https://github.com/user-attachments/assets/68377f8b-b980-4e18-a210-a1cd0e8e3621)


In the forecast of price trends in the year 2025 in the city of Chennai, 8 ARIMA models were developed and the metrics were obtained as follows:
![image](https://github.com/user-attachments/assets/edc1af58-4ee7-4d20-a066-97c9c6bc1fe3)


For the data pertainign to each of the cities, Model 6 is the best performing model as all its metrics are least as compared to others.


## Real Estate Dashboard

The link to the Dashboard: https://public.tableau.com/app/profile/a.a83892683/viz/realestatedashboard_17276852344990/Dashboard1?publish=yes



## Forecast for 2025 Price Trend

The following graph illustrates the forecasted price trend in 2025 for Hyderabad
![image](https://github.com/user-attachments/assets/e34bb9e7-1aef-4480-8ef3-4c6da414ea3d)


The following graph illustrates the forecasted price trend in 2025 for Bangalore
![image](https://github.com/user-attachments/assets/fdab75ff-0f34-4b1b-ac0d-3fae35825ab2)

The following graph illustrates the forecasted price trend in 2025 for Chennai
![image](https://github.com/user-attachments/assets/f2d5527d-a8b3-4a8d-86c3-f5f88dc845f5)
