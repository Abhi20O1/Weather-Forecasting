# Weather Forecasting Pipeline

A learning project that collects weather observations, trains a Random Forest classifier, and produces a weather-condition prediction from recent measurements.

## Pipeline

1. Fetch weather data from OpenWeatherMap.
2. Append processed observations to a CSV dataset.
3. Train a scikit-learn Random Forest model.
4. Save the model with Joblib.
5. Generate a prediction from recent numeric features.

## Technology

Python · Pandas · Requests · scikit-learn · Joblib · Schedule · Jupyter Notebook

## Run safely

Set the OpenWeatherMap key as an environment variable and update the city/configuration before running. Do not place API keys directly in notebooks or source files.

```bash
pip install pandas requests scikit-learn joblib schedule jupyter
jupyter notebook
```

The repository includes the notebook workflow, data directories, model artifacts, and supporting scripts. Validate data freshness, time-based splits, class balance, and forecast metrics before treating the output as a real forecast.
