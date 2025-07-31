In this project, I developed a stock price prediction model using Long Short-Term Memory (LSTM), a type of recurrent neural network well-suited for time series 
forecasting. The goal was to predict future closing prices of stocks based on historical trends. To enhance the model’s learning ability, I used two key technical 
indicators as input features: the 50-day Moving Average (MA50) and the 200-day Moving Average (MA200). MA50 captures short- to mid-term price trends by averaging 
the last 50 days of stock prices, making the model more responsive to recent market movements. In contrast, MA200 provides a long-term perspective by averaging the
past 200 days, helping the model understand overall trend direction and reducing sensitivity to short-term volatility. Together, these features give the LSTM model
a balanced view of both recent momentum and long-term market behavior, improving the accuracy and reliability of future price predictions.

How to Run the project 
To run this project, first ensure that Python is installed on your system along with the required libraries such as pandas, numpy, matplotlib, yfinance, sklearn, 
and torch. Begin by cloning the repository or downloading the project files. Then, open the Jupyter notebook or Python script and specify the stock symbol along with 
the start and end dates for fetching historical data. The data is preprocessed, including feature scaling and sequence generation, before being fed into the LSTM
model for training. After training, the model predicts stock prices for the next 15 days. The results are visualized by plotting actual vs. predicted prices for 
performance evaluation.
