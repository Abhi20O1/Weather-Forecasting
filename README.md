# Weather-Forecasting

Project Overview

This project builds an automated machine learning pipeline to forecast weather conditions using historical data fetched from the OpenWeatherMap API. It trains a supervised model to predict weather metrics like temperature and precipitation, updates predictions hourly. This is useful for agriculture, logistics, and event planning where real-time weather awareness is crucial.

Key Features & Technologies

  1. Automated Data FetchingFetches weather data for the last 5 hours from OpenWeatherMap.

  2. Machine Learning ModelTrains a model to predict future weather conditions (e.g., temperature, rain).

  3. Hourly SchedulerUses schedule module to update data, retrain, and predict every hour.

  4. Pandas, Scikit-learn, OpenWeatherMap API, Joblib, Schedule, Jupyter Notebook
