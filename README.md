#  Optiver - Trading at the Close
Predict US stocks closing movements

## Overview
Developing a model capable of predicting the closing price movements for hundreds of Nasdaq listed stocks using data from the order book and the closing auction of the stock. Information from the auction can be used to adjust prices, assess supply and demand dynamics, and identify trading opportunities.

## Evaluation
Submissions are evaluated on the Mean Absolute Error (MAE) between the predicted return and the observed target

## Submission
Selected submissions include a model of LightGBM tuned through Optuna obtaining MAE of 5.50 <br> and a model of XGBoost with MAE score of 5.45
