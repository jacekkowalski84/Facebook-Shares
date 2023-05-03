# Facebook Stock Analysis

This program analyzes the dataset of Facebook stock share prices and volume and creates a dashboard that shows changes in prices over time. The dashboard helps investors decide when to invest and when to sell stock shares.

# Data
The data used in this program is in the 'fb.csv' file located in the 'data' folder. The data contains the following columns:


1. Date: date of the stock price

2. Close/Last: closing price of the stock

3. Volume: volume of shares traded

4. Open: daily opening price of the stock

5. High: daily highest price of the stock

6. Low: daily lowest price of the stock

# Data Processing
The data is processed using pandas library to remove dollar signs from the 'Close/Last', 'Open', 'High', and 'Low' columns, and sort the data by date. The program also calculates the rolling average of the 'Open' column over the last 14 days and assigns it to a new column called 'Open_Average'. The data is then plotted using the 'plot' function in pandas.

# How to use
Open the Jupyter Notebook file and run the code.
The program will display a dashboard that shows changes in prices over time.

# Code and Resources Used
Python Version: 3.9.7

Packages: pandas

Data Source: Yahoo Finance (https://finance.yahoo.com/quote/FB/history/)

# Future Improvements

Adding more interactive features to the dashboard, such as filters and dropdowns.

Adding more visualizations, such as moving average and candlestick charts.

Using machine learning algorithms to predict future stock prices.
