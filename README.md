# :earth_americas: GDP dashboard template

A simple Streamlit app showing the GDP of different countries in the world.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://gdp-dashboard-template.streamlit.app/)

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```

# Furniture Sales Forecasting

## Project Overview
The Furniture Sales Forecasting project is designed to predict future sales using time series analysis techniques. This project implements ARIMA and Prophet models for forecasting, integrates a Flask API for predictions, and provides an interactive Streamlit dashboard for visualization and exploratory data analysis (EDA).

## Features
1. **Time Series Forecasting**:
   - Models used: ARIMA and Prophet.
   - Forecasts sales for a user-defined period with confidence intervals.

2. **Interactive Dashboard**:
   - **Home Tab**: Displays forecasted sales as a graph and a table with confidence intervals.
   - **EDA Tab**: Provides insights into the dataset with detailed visualizations using data profiling.

3. **API Integration**:
   - A Flask API serves the forecasted data to the Streamlit app.

## Project Structure
```plaintext
FurnitureSalesForecast/
├── streamlit_app.py       # Streamlit dashboard code
├── api.py                 # Flask API code
├── prophet_model.pkl      # Trained Prophet model
├── requirements.txt       # Dependencies
├── cleaned_super_store_data.csv  # Default dataset for EDA
├── Project Journal.docx   # Detailed project documentation


Instructions
1. Setup Environment
Install dependencies:
bash
Copy code
pip install -r requirements.txt
2. Run Flask API
Start the API server:
bash
Copy code
python api.py
The API runs on: http://127.0.0.1:5000/forecast.
3. Run Streamlit Dashboard
Launch the dashboard:
bash
Copy code
streamlit run streamlit_app.py
Interact with the Home and EDA tabs for forecasts and data analysis.
4. Test the API
Use tools like Postman to test the /forecast endpoint.
Highlights
The Streamlit app dynamically adjusts forecasts based on user input.
EDA is cached to improve performance and reduce reloading time.
The deployed model offers accurate forecasts with confidence intervals.
Deployment Links
[Furniture Sales Forecasting Streamlit Dashboard](https://ts-dashboard-ft317gdnpk.streamlit.app/)
