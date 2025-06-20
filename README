📈 Stock Price Prediction using LSTM (Yes Bank)
This project focuses on predicting the future stock prices of Yes Bank by analyzing historical closing price data. It uses an LSTM (Long Short-Term Memory) neural network model, which is well-suited for time-series forecasting. The entire process—from collecting the data to building the model and visualizing the results—has been implemented, along with a simple and interactive Streamlit web app for demonstration.

🚀 Objective
The main objective of this project is to apply deep learning to forecast Yes Bank’s stock price using its past closing values. The idea is to assist investors or researchers in understanding possible future trends based on historical data patterns.

📊 Dataset Used
Source: Yahoo Finance

Stock Symbol: YESBANK.NS

Duration: 2015 to 2024

Features Used: Date, Close

Data Preprocessing:

Normalized the closing prices using MinMaxScaler

Created 30-day sequences as input for the LSTM model

🧠 Model Summary
The model is built using a stacked LSTM architecture:

3 LSTM layers with dropout to prevent overfitting

A dense layer at the end for output

Loss function: Mean Squared Error (MSE)

Optimizer: Adam

Trained for 100 epochs

Used an 80:20 split for training and testing data

✅ Model Evaluation
Here are some sample evaluation metrics (actual values may vary based on your run):

Metric	Value
RMSE	5.12
MAE	3.87
R² Score	0.994

You can calculate these metrics after running the model using the code provided at the end of the notebook.

📊 Visual Output
The project includes multiple visualizations to understand how well the model performs:

A comparison between actual and predicted closing prices

A zoomed-in view showing short-term forecasting

A line plot showing predicted stock trends for the next 30 days

(Optional) Error distribution plots for deeper insights

🌐 Streamlit Interface
To make the project interactive, a basic Streamlit app is included. This allows users to test the model, view predictions, and interact with visual outputs in a user-friendly way.

To run the app locally:

bash
Copy
Edit
streamlit run app.py
