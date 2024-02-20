# Bitcoin-Price-Prediction-Using-ARIMA-model
Here we will see the forecasted results accuracy using the ARIMA model <br>
Firstly we will install the yfinance to extract bitcoin prices using yahoo finance<br>
Then we will import all the necessary libraries<br>
Then will split the model into train and test<br>
Then plot the train and test graph to get a clear representation <br>
Now let's build the ARIMA model<br>
We will write the ARIMA model which will be Rolling model because we are using the historical data in order to predict the future data, so if in case it starts t=0 for example in this case by saying t=0 we mean at this point if it starts then we go in future so the historic window in the ARIMA model will be increasing
so we need to change the training set for all iterations and then that will be used to predict the prices<br>
The No's which we use here are p,d,q that are auto ARIMA model which actually does simulations for different numbers of p,q,d this gives us the best numbers which should be used as p,q,d<br>
As this model overlaps so to predict prices right we wrote the formula for M-A-P-E (mean absolute percentage error) the formula is we subtract the mean prediction value with the absolute value and divide it with actual value to calculate the MAPE value<br>
Around 1.49% MAPE implies the model is about 98.51% accurate in predicting the test set observations. The best value for MAPE is 0.0 but,mape suggests that there is 1.5% error in the forecasted value

