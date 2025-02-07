# AQI Prediction Using XGBoost

## Project Overview

This project focuses on predicting the Air Quality Index (AQI) for Dhaka using data collected from 2016 to 2022. The objective was to build a machine learning model that can forecast AQI values for the year 2025, based on historical trends.

The dataset includes over 51,000 hourly AQI records, and to make accurate predictions, I utilized **XGBoost**, a powerful gradient boosting machine learning algorithm. The project involved several stages, from data cleaning and feature engineering to training the model and evaluating its performance.

## Key Highlights

- **Data Coverage**: The dataset spans from 2016 to 2022, with hourly AQI data points collected across multiple years.
- **Prediction Target**: The model predicts AQI values for Dhaka in 2025.
- **Model Used**: XGBoost, which is known for its efficiency and performance in predictive tasks.
- **Performance Metrics**:
  - **R-squared (R²)**: 93% – This indicates that the model is able to explain 93% of the variance in the AQI data, demonstrating strong predictive power.
  - **RMSE (Root Mean Squared Error)**: 19.7924 – A relatively low error value, suggesting that the model’s predictions are close to the actual values.

## Data Preparation

The dataset required several preprocessing steps to ensure the model could learn effectively:

- **Data Cleaning**: Removed outliers and unnecessary columns, ensuring the dataset was well-structured for analysis.
- **Feature Engineering**: Created time-based features to capture the patterns in the AQI values over different hours of the day.
- **Train-Test Split**: Used data from 2016 to 2020 for training the model, while 2021 to 2022 was used for testing its accuracy.

## Model and Evaluation

The XGBoost model was trained using the historical data and tested on the more recent two years. The model showed excellent performance with:

- **R-squared (R²)**: 93%, indicating it explained a significant portion of the variance in AQI.
- **RMSE (Root Mean Squared Error)**: 19.7924, suggesting that the predictions are highly accurate and close to the actual AQI values.

## Conclusion

This project successfully forecasts Dhaka’s AQI for 2025 with high accuracy. The model can be applied to other cities or extended for real-time forecasting by integrating new data.

Although the model performed well, there’s always room for improvement. Future work could include experimenting with different algorithms or adding additional features like weather data to further enhance the model's predictions.

## Future Work

- Experiment with other machine learning algorithms such as Random Forest or LSTM.
- Add more features, such as temperature and humidity, to improve prediction accuracy.
- Fine-tune the model's hyperparameters for further optimization.
