# Multiple_Linear_Regression_to_predict_Close_Values
Multiple Linear Regression is applied on stock market data to predict Close values. Data is obtained from MongoDB
Download .py and .csv file and put them in same folder together. Make sure to set console working directory so that .py file can read the data from .csv file.
70%split (High, Low and Open) is the result when I used High, Low and Open as input. (This option was preffered).
70%split (High,Low,Open and Bearish) is the result when I used High, Low, Open and Bearish as input but result wasnt much different when using (High, Low and Open).(This option was discarded because of extra computations).
70%split (High,Low,Open,Bearish, and Bullish) is the result when I used High, Low, Open, Bearish and Bullish as Input. Inclusion of Bullish make predictions really bad. (This option was discarded).
