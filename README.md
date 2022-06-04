# Yes_bank-stock-pred


**Abstract**

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has
been in news because of the fraud case involving Rana Kapoor.
Owing to this fact, it was interesting to see how that impacted the stock prices of
the company and whether Time series models or any other predictive models can
do justice to such situations.
This dataset has monthly stock prices of the bank since its inception and includes
closing, starting, highest and lowest stock prices of every month.


**Problem Statement**


Time Series forecasting & modeling plays an important role in data analysis. Time
series analysis is a specialized branch of statistics used extensively in fields such as
Econometrics & Operation Research.
The given dataset is of Stock prices of Yes bank and our main
objective is to predict the stock’s closing price of the month.


**Dataset Summary**


There are multiple variables in the dataset – date, open, high, low, close.
The columns Open and Close represent the starting and final price at which the
stock is traded on a particular day.
High and Low represent the maximum, minimum of the share for the day.
The given dataset consist of 185 rows and 5 columns, the columns description is as
follow:


1. The dataset contains multiple variables - date, open, high, low and close.
2. 
3. The column date contains the month and the year of the price of the share.
4. 
5. The columns Open and Close represent the starting and final price at which the
stock is traded in a particular month.

4. High and Low represent the maximum and minimum price of the share for the
month.

5. The profit or loss calculation is usually determined by the closing price of a
stock for the month; hence we will consider the closing price as the target
variable.


**Steps involved:**


1. Importing important libraries to be used.
2. 
3. Mounting the drive and loading the dataset.
4. 
5. Exploratory data Analysis
6. 
7. Data extraction and manipulation.
8. 
9. Splitting the data using TimeseriesSplit.
10. 
11. Fitting the dataset over various models like linear regression, random
forest, KNN, XGBoost, Gradient Boost.

7. Using Facebook Prophet library for lag creation and forecasting.
8. 
9. Using Auto ARIMA to better understand the data set and predicting
future trends.


**Conclusion**


We have predicted the stock prices using different methods in this project. We
have used simple machine learning linear regression, then have used FBProphet
package and implemented linear regression, regularization techniques, bayesean
ridge, adaboost, xgboost, random forest and knn techniques.
We also have used two ways of splitting the data into train and test set one is train
test split and other is timeseriessplit
Also we have implemented Time series Analysis using ARIMA and
SARIMA (Checked stationarity of the model too).
Out of these we found Linear regression, regualrization technique, Random
Forest and Auto Arima model working very fine in predicting stock prices for
the Yes Bank.
