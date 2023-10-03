# StockPredictor
Created a Stock Predictor in a Jupyter Notebook by utilizing Python, Pandas, SciKit Learn and Keras

Here are some images and details

Initializing libraries and printed out SP500 stock information

![image](https://github.com/husaab/StockPredictor/assets/126218851/36675666-e566-4897-987c-a41127bb0d18)

Deleted Dividends and Stock Splits, as they are irrelevant data for us, also added a Tomorrow column, which is equal to the Stock Price the next day

![image](https://github.com/husaab/StockPredictor/assets/126218851/b9b153f5-3daa-4cfc-a737-402f209f205f)

Removed all data from before 1990 to make model more accurate with its predictions.
Added a random forest classifier, which helps with analyzing non-linear patterns
Initialized predictors as Close, Volume, Open, High and Low, these predictors will be used to predict the stock

![image](https://github.com/husaab/StockPredictor/assets/126218851/ff86f7df-3c15-461e-8033-902e9b98e5d1)

Using the model to test with the predictors.

![image](https://github.com/husaab/StockPredictor/assets/126218851/b8b62df5-9ad1-4d9a-92b7-26ed555107ca)

Created a function for predictors to simplify the code

Created a backtesting algorithm to predict a more accurate share price/precision score

![image](https://github.com/husaab/StockPredictor/assets/126218851/d292ec76-9df7-42b0-a994-05013b745439)

Added new predictors to make the machine learning model more accurate with its predictions

![image](https://github.com/husaab/StockPredictor/assets/126218851/a6e4177d-2ab2-4975-9ca4-f781dc2c1916)








