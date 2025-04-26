# Sequence-Text-Prediction-using-LSTM
Sequence Text Prediction using LSTM
## Course
**Deep Learning**

## Lab Title
**LSTM Time Series Forecasting**

## Students
- **Rutuja Udanshiv** (ID: 202201040120)
- **Nilambari Mahajan** (ID: 202201040118)

## Date of Submission
26-04-2025

## Objective
The objective of this assignment is to explore Long Short-Term Memory (LSTM) networks for sequential data problems, specifically:

1. **Time Series Forecasting**: Predicting future values of a univariate time series using LSTM models to understand patterns and trends.

## Experiment 5.1 - Time Series Forecasting

### Dataset
- **Sunspot Activity Dataset**  
  (Monthly Mean Total Sunspot Number)

### Methodology
- **Data Loading**: Read the sunspot dataset using pandas.
- **Preprocessing**: Normalized the dataset using MinMaxScaler.
- **Sequence Creation**: Prepared input sequences using a sliding window approach.
- **Model Building**: Built a Sequential LSTM model using Keras.
- **Training**: Model trained over 30 epochs with Adam optimizer and Mean Squared Error loss.
- **Prediction**: Forecasted future sunspot values.
- **Evaluation**: Visual comparison through Actual vs Predicted plots and calculation of RMSE/MAE.

### Libraries Used
- pandas
- numpy
- matplotlib
- sklearn
- keras

### Results
- **Visualization**: A plot showing the predicted vs actual sunspot numbers.
- **Metrics**: RMSE and MAE values were calculated to evaluate model performance.

---

## How to Run
1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib scikit-learn keras

