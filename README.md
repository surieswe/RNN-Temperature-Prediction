# RNN Temperature Prediction

## Project Overview
This project uses a Recurrent Neural Network (RNN) to predict the next day's temperature from historical daily temperature readings.

## Objective
Predict the next day's temperature using the previous 7 or 30 days of temperature data.

## Technologies Used
- Python
- Google Colab
- TensorFlow and Keras
- NumPy and Pandas
- Matplotlib
- Scikit-learn

## Workflow
1. Load and explore historical temperature data.
2. Preprocess the temperature values.
3. Create input sequences using the previous 7 or 30 days.
4. Split the time-series data into training, validation, and test sets.
5. Build and train a SimpleRNN model.
6. Evaluate predictions using MAE and RMSE.
7. Predict the next day's temperature.

## Evaluation
The model was evaluated against a baseline that predicts the next day's temperature using the most recent observed temperature.

## How to Run
Open the `.ipynb` notebook in Google Colab and run the cells in order.

## Learning Outcome
Learned how recurrent neural networks process sequential data and how to build a basic time-series forecasting model.
