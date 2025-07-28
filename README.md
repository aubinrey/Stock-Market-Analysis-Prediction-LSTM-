# Stock-Market-Analysis-Prediction-LSTM

Time series data consists of sequential data points indexed by time. Because time series data is everywhere—from finance to weather forecasting—being able to analyze and manipulate it is a vital skill for any data analyst or data scientist.

In this project, I explore and analyze stock market data, focusing on major technology companies: Apple, Amazon, Google, and Microsoft. Using the **yfinance** library, I retrieve historical stock data and visualize various insights with **Seaborn** and **Matplotlib**.

The analysis covers stock risk assessment based on historical performance and forecasting future stock prices using a **Long Short-Term Memory (LSTM)** neural network.

---

## Objectives

Throughout this project, I aim to answer several important questions:

1. How have the stock prices changed over time?  
2. What is the average daily return for each stock?  
3. What are the moving averages for the stocks?  
4. How are the stocks correlated with each other?  
5. What is the potential risk exposure when investing in these stocks?  
6. How can future stock prices be predicted? (Specifically, predicting Apple’s closing price with an LSTM model)

---

## Data Acquisition

The first step is obtaining the data and loading it for analysis. I use **Yahoo Finance**, a comprehensive platform providing financial market data and investment insights. The Python package **yfinance** offers a convenient, threaded, and Pythonic interface to download historical market data directly from Yahoo Finance.

For more details on yfinance, visit:  
[Reliably download historical market data from Yahoo with Python](https://aroussi.com/post/python-yahoo-finance)

---

Feel free to explore the project and learn how time series analysis and LSTM modeling can be applied to stock market prediction!
