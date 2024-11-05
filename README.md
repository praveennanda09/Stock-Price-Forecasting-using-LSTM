# Stock Price Forecasting Using LSTM

## Overview
This project focuses on building a Stock Price Forecasting Model using Long Short-Term Memory (LSTM) networks, a type of Recurrent Neural Network (RNN) well-suited for time series data. The model aims to predict future stock prices by analyzing historical stock prices and trends. Stock price prediction is crucial for investors and financial analysts to make informed decisions in trading and investment.

## Dataset
The dataset used for this project consists of 851,255 rows and 7 columns, covering multiple companies’ stock prices across various dates. Each row in the dataset includes:

- **date**: The date of the stock data entry (e.g., 05-05-2011)
- **symbol**: The stock ticker symbol (e.g., "EW" for Edwards Lifesciences)
- **open**: Opening price of the stock for the day
- **close**: Closing price of the stock for the day
- **low**: The lowest price reached during the day
- **high**: The highest price reached during the day
- **volume**: Number of shares traded during the day

## Project Goals
- **Predict future stock prices** based on historical data using LSTM networks.
- **Analyze the trends** in stock price fluctuations and forecast the closing price.
- Provide insights to help investors make data-driven trading decisions.

## Approach
1. **Data Preprocessing**: 
   - Cleaned and prepared the dataset, including handling missing values if any, and transforming the data into a format suitable for LSTM.
   - Feature selection and scaling.
2. **Feature Engineering**:
   - Selected relevant features (e.g., `open`, `close`, `high`, `low`, `volume`) for time series forecasting.
   - Converted the data into sequences for input to the LSTM model.

3. **Model Architecture**:
   - Developed an LSTM-based model to capture temporal dependencies in stock prices.
   - Tuned hyperparameters like the number of LSTM layers, hidden units, batch size, and epochs to optimize model performance.

4. **Training & Evaluation**:
   - Trained the model on the historical stock prices to learn patterns in price movement.
   - Evaluated the model using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to measure forecasting accuracy.

5. **Prediction**:
   - Used the trained LSTM model to forecast future stock prices based on recent historical data.

## Results
The LSTM model achieved promising accuracy in predicting the closing stock prices. This performance suggests that LSTM networks can effectively capture trends and patterns in historical stock price data, making them valuable for forecasting.

## Conclusion
- The LSTM model effectively predicts stock prices, aiding in the assessment of future trends.
- By accurately forecasting prices, this model provides insights that can support better investment and trading decisions.
- **Future Improvements**: Incorporate additional features like technical indicators, sentiment analysis of financial news, or macroeconomic data to improve the model's forecasting ability further.


