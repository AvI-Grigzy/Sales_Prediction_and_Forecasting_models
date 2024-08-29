# Sales Prediction and Forecasting Models

This repository contains a Jupyter Notebook that demonstrates various techniques for sales prediction and forecasting using machine learning models. The notebook is structured to guide you through the process of generating synthetic sales data, applying different models for prediction, and visualizing the results.

## Features

- **Simple Linear Regression Model**:
  - Predicts sales based on a simple linear relationship between time (days) and sales.
  - Evaluates the model's performance using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
  - Visualizes the actual versus predicted sales and forecasts future sales.

- **Synthetic Sales Data Generation**:
  - Generates a year's worth of daily sales data with an upward trend using a Poisson distribution.
  - Saves the generated data to a CSV file for further analysis or modeling.

- **ARIMA Model**:
  - The ARIMA (AutoRegressive Integrated Moving Average) model is another powerful tool for time series forecasting, particularly when your data shows strong temporal correlations. 

- **Prophet Model**:
  - A section dedicated to sales prediction using Prophet model for time series forecasting.

## Getting Started

### Prerequisites

To run the notebook, you will need the following Python packages:

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `prophet` 


### Installing Dependencies

Ensure that you have Python installed on your system. You can install the required Python packages using pip:

```bash
pip install pandas numpy matplotlib scikit-learn prophet
```

### Usage
1. Clone the repository:
```bash
git clone https://github.com/AvI-Grigzy/Sales_Prediction_and_Forecasting_models.git
```
2. Run the Jupyter Notebook:
   
Launch Jupyter Notebook in your terminal and open sales_prediction_and_forecasting_models.ipynb

3. Execute the cells:

Follow along with the notebook, executing each cell to generate synthetic data, train models, and visualize predictions.
