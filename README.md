README.txt

------------------------------------------------------------
Project Title: EnergyWise - Predicting Energy Consumption
------------------------------------------------------------

Student Name   : Priadharshni P  
Platform       : Google Colab  
Language Used  : Python  
Libraries Used : pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost  

------------------------------------------------------------
Project Overview:
------------------------------------------------------------
EnergyWise is a machine learning project aimed at forecasting energy consumption patterns in residential and commercial buildings. The model uses historical energy usage, weather data, and occupancy patterns to make predictions.

The project includes:
- Data exploration and cleaning
- Feature engineering (lag features, rolling stats, time features)
- Correlation and trend visualizations
- Training a predictive model using XGBoost
- Model evaluation using MAE, MSE, RMSE
- Generating insights like smart alerts and forecast charts

------------------------------------------------------------
Model Details:
------------------------------------------------------------
- Model Used: XGBoost Regressor
- Target Variable: Active Power Consumption
- Evaluation Metrics: MAE, MSE, RMSE
- Prediction Output: Forecasts for upcoming energy usage and alerts on high usage

------------------------------------------------------------
How to Run:
------------------------------------------------------------
1. Open the notebook in Google Colab.
2. Upload the dataset: `energy_weather_raw_data.csv`
3. Run each cell sequentially for data preprocessing, modeling, and prediction.
4. Final sections will display graphs, insights, and forecast messages.

------------------------------------------------------------
Use Case:
------------------------------------------------------------
This project demonstrates the use of AI in energy management systems to provide users with proactive insights for reducing power consumption and identifying unusual patterns.

------------------------------------------------------------
