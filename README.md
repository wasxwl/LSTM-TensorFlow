LSTM-TensorFlow

    Stock trading trend prediction is one of the tasks involved in quantitative trading, which is to analyze and predict price trends through statistics and machine learning. Generally, we can use time series related modeling methods, but this challenge will try to use LSTM to complete stock prediction analysis.
    This challenge only uses Microsoft’s historical data after 2010, and specifies Adj. Close’s adjusted closing price as the prediction object. The challenge uses data before 2018 as training data and data after 2018 as test data.

Requirements

    Python 3.12.4
    tensorflow 2.17.0
    pip install quandl

    We obtain real-time stock trading data. The Quandl financial data module is selected here. The challenge requires first installing the Python library provided by Quandl. Unregistered Quandl users can submit 50 access requests per day, and there is no limit for registered accounts. This experiment uses the test account provided by the course. If you use it yourself, please register for free through the official website to obtain the API KEY.