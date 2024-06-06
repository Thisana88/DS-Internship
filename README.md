# Cryptocurrency Mean Reversion Trading Strategies: Jupyter Notebook Project

## Description

This Jupyter Notebook project explores mean reversion trading strategies using cryptocurrency data, specifically Bitcoin (BTC) and Avalanche (AVAX). It includes data preparation, cleaning, statistical analysis, and implementation of trading strategies. The project aims to provide insights into mean reversion principles and their application in financial markets.

## Installation

To run this project, you need to have Python installed on your system along with the following libraries:

    yfinance
    pandas
    numpy
    seaborn
    matplotlib
    pandas_datareader
    arch

You can install these libraries using pip:

    pip install yfinance 

## Usage

Clone the Repository: Clone this repository to your local machine.

Open Jupyter Notebook: Navigate to the directory containing the notebook file (mean_reversion.ipynb) and open it using Jupyter Notebook.

Run Cells: Execute each cell in the notebook sequentially by pressing Shift + Enter.

Explore the Project: Read through the project's content, including data preparation, analysis, and trading strategies.

Experiment: Feel free to experiment with the code, modify parameters, or add new analysis techniques.

## Contents

Statistical Analysis

Statistical tests like the Augmented Dickey-Fuller (ADF) test and Phillips-Perron (PP) test are performed to assess stationarity and identify potential mean reversion opportunities in the price series.

Mean Reversion Strategy

A mean reversion trading strategy is implemented based on Z-scores of the spread difference between BTC and AVAX. Potential buy and sell signals are identified when the Z-score crosses predefined thresholds.
Pairs Trading

A pairs trading strategy is explored based on the historical spread difference between BTC and AVAX, defining entry and exit thresholds to initiate and exit positions.
Machine Learning Algorithms

A Decision Tree classifier is applied to predict mean reversion signals using various features derived from the data. The model's performance is evaluated using accuracy, precision, recall, and F1-score metrics.

## Results

The project provides insights into the effectiveness of mean reversion strategies and compares different trading approaches. Key findings include correlations between cryptocurrency prices and the mean reversion signals.

## Conclusion

Mean reversion strategies offer potential opportunities for profit in financial markets, but their success depends on various factors such as market conditions, asset selection, and risk management.The overall model suggests that the machine learning model could support mean reversion algorithms for trading with BTC and AVAX. Further experimentation and validation are recommended before deploying these strategies in live trading environments.

## Acknowledgments

Special thanks to Yahoo Finance for providing cryptocurrency data.
Inspired by the work of financial analysts and data scientists in the field of algorithmic trading.
