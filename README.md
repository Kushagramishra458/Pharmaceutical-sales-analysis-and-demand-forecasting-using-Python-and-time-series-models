# Pharmaceutical Inventory Demand Analysis & Forecasting

## Project Overview

This project analyzes pharmaceutical inventory and sales data to explore demand patterns and forecasting techniques. Using Python, data analysis, time-series forecasting, and machine learning, the project examines historical sales trends and evaluates different approaches for predicting demand.

The objective is to understand how historical data and forecasting models can support better pharmaceutical inventory planning and replenishment decisions.

## Objectives

- Analyze pharmaceutical sales and inventory data.
- Identify sales trends and variations in product demand.
- Apply time-series forecasting and machine learning techniques.
- Evaluate model performance using appropriate error metrics.
- Explore the role of demand forecasting in inventory management.

## Tools and Technologies

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib
- **Machine Learning:** Scikit-learn
- **Time-Series Forecasting:** ARIMA, Holt-Winters
- **Models:** Random Forest, Linear Regression
- **Evaluation Metrics:** MAE, MSE, RMSE, MAPE

## Dataset

The project uses a pharmaceutical inventory dataset containing historical sales and related product information. The data is used to examine demand patterns, prepare data for analysis, and explore forecasting techniques.

## Project Workflow

### 1. Data Preprocessing

- Load and inspect the dataset.
- Examine data quality and missing values.
- Prepare the relevant data for analysis and forecasting.

### 2. Exploratory Data Analysis

- Analyze historical sales and demand patterns.
- Examine variations in sales over time.
- Identify trends and patterns relevant to inventory planning.

### 3. Demand Forecasting

**ARIMA**

ARIMA is used to model time-series observations and explore future demand based on historical patterns.

**Holt-Winters**

Holt-Winters exponential smoothing is used to model time-series data where level, trend, and seasonality may be relevant.

### 4. Machine Learning

Random Forest and Linear Regression are explored as prediction approaches for analyzing relationships in the available data.

### 5. Model Evaluation

Forecasting and prediction performance is assessed using applicable evaluation metrics:

- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **MAPE:** Mean Absolute Percentage Error

These metrics help assess the difference between predicted and actual values.

## Results

The project explores multiple forecasting and prediction techniques for pharmaceutical sales and demand analysis.

| Model | Evaluation Metric | Value |
|---|---|---:|
| Holt-Winters | RMSE | 5032.71 |
| Random Forest | MSE | 111.61 |
| Linear Regression | MSE | 159.58 |

The values above should be interpreted according to the evaluation procedure used for each model. Since different metrics have different scales and meanings, they cannot be compared directly to determine which model performs best.

## Applications

Demand forecasting can help support:

- Pharmaceutical demand planning.
- Inventory monitoring and replenishment.
- Identification of changes in sales patterns.
- Stock availability planning.
- Data-driven inventory management decisions.

## Future Improvements

- Improve forecasting accuracy through systematic model comparison.
- Use chronological training and testing data for time-series evaluation.
- Compare forecasting models against baseline methods.
- Incorporate supplier lead times and stock availability.
- Explore reorder points, safety stock, and Economic Order Quantity (EOQ).
- Develop an interactive dashboard for demand and inventory monitoring.

## How to Run

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab

### Installation

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib scikit-learn statsmodels jupyter
