# Time-Series-Analysis

In this assignment, I used time series and a linear regression models to predict future movements in the foreign exchange between the Yen and United States Dollar.

I applied 29 years of USD to JPY exchange rate data from January 1990 through October of last year. I created and utilized the following models to make predictions on various elements of the Yen over the next 5 trading days. The models I used were ARMA, ARIMA, and GARCH. The ARMA model was used to forecast the projected returns while the ARIMA model was utilized to predict the price. To make sure these models are accurate I used the GARCH model to predict the possible volatility.

According to these models, they predicted that returns on the Yen should fall vs. the United States Dollar, and volatility should rise. The models can draw the conclusion that it would be a bad invest in the Yen over a the long term. There are other factors to consider, because of the high p-value for the models it is not completely accurate. Personally, I would not put all of my trust in the outcome of these models.

After deciphering the data I applied the same dataset to create a linear regression model. This was to try and predict returns for the yen. The model was trained from 1990-2018. Once the time frame was set I inputted the in sample and out of sample from 2019 to determine the accuracy of the original model. When the outputs were compared the root mean squared error for the out of sample application was less than the in sample application. This showed that the model could be used to make a partially accurate prediction on data sets it is not familiar with.
