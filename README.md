# algobulls
A moving average based strategy developed in python

# Requirements

To run this project, you need to have the following dependencies installed:

pandas
requests

# Code Blocks

The project consists of the following code blocks:

ScriptData: This class fetches intraday stock data using the Alpha Vantage API. The data is also converted to data frames

indicator1: This function takes data frames and a time period as inputs and computes the moving average indicator based on the 'close' column.

Strategy: This class utilizes the ScriptData class and indicator1 function to fetch stock data, compute the indicator, and generate trading signals based on the indicator and closing prices. It provides a method to get the signals.
