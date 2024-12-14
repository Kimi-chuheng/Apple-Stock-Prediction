#Apple Stock Price Prediction Using LSTM

## Project Overview
This project is part of my Data Science research work at UMKC. The goal of this project was to predict the stock price of Apple Inc. using historical stock data and news articles. The dataset used in this project can be found on Kaggle: [Apple Stock Data](https://www.kaggle.com/datasets/varpit94/apple-stock-data-updated-till-22jun2021/data).

**Project Date**: October 2024

## Dataset Information
The dataset used for this project includes Apple stock history data. It contains daily stock price information such as:
- Open price
- Close price
- Adj Close price
- Highest price
- Lowest price
- Volume

You can access and download the dataset from [here](https://www.kaggle.com/datasets/varpit94/apple-stock-data-updated-till-22jun2021/data).

Additionally, I also experimented with incorporating news data from Apple's archive, although the results were less than expected.

## Approach

### 1. Stock Price Prediction with LSTM
I implemented a Long Short-Term Memory (LSTM) model to predict future stock prices based on historical stock data.  
The results were reasonable, but there may be potential for further improvements in model architecture and hyperparameter tuning.

### 2. Incorporating News Data
I tried using Apple's historical news data to enhance the prediction model. ([Apple News Archive](https://www.apple.com/newsroom/archive/))  
The idea was to use sentiment analysis on the news articles to gauge how external factors (news events) impact stock prices.  
Unfortunately, the results from the news data were not as effective as anticipated, and the accuracy of predictions did not improve significantly.

## Future Work
The current model could be further improved once more reliable and comprehensive news data becomes available. I plan to refine the approach by incorporating more features such as:
- Improved sentiment analysis techniques.
- Use of external data sources like financial reports and macroeconomic indicators.


