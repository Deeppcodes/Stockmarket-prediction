# 📈 S&P 500 Stock Movement Predictor

This project uses historical S&P 500 data to predict whether the index will go up the next day, based on various technical indicators and a Random Forest classifier.

# 🔧 Technologies Used

Python
yfinance
pandas
matplotlib
scikit-learn

# 📊 Features

Downloads S&P 500 data from 1927 to present using yfinance

Engineers features like:

Tomorrow’s price (shift)
Target variable (whether price increased)

Rolling mean ratios (e.g., Close / MA(60))

Rolling trends (e.g., number of up days in past 250 days)

Trains a RandomForestClassifier

Implements rolling-window backtesting with precision evaluation

Uses thresholded probabilities for more confident predictions


# 🧪 Backtesting Strategy
Train on past i rows and test on the next step rows
Repeats until end of dataset
Aggregates predictions for analysis
