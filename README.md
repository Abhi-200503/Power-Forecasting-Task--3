# Power Consumption Forecasting – Task 3

## Task Objective

Connect the power consumption forecasting results with a natural-language interface so that users can ask questions about historical consumption, future forecasts, and model performance.

## Features

- Power consumption dashboard
- Historical power consumption analysis
- Next 24-hour power forecasting
- Random Forest model performance evaluation
- Natural-language query interface
- Predicted peak, minimum, and average consumption
- Historical peak and minimum analysis
- Recent and top consumption readings
- MAE, RMSE and R² model metrics

## Natural Language Queries

Example questions:

- What is the average power consumption?
- What was the peak power consumption?
- Show the last 10 readings.
- Show the top 10 peak readings.
- Show the next 24-hour forecast.
- What is the predicted average consumption?
- What is the predicted peak consumption?
- What is the predicted minimum consumption?
- What is the model performance?
- How many records are available?

## Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Joblib

## Project Structure

```text
Power-Forecasting-Task-3/
├── app.py
├── requirements.txt
└── data/
    ├── power_consumption_model_small.pkl
    └── processed_power_consumption.csv
