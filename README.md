# Oil_forecasting_project2
Forecasting crude oil prices in the US using monthly data
For this project AR, MA, and ARIMA models were constructed using univariate data. The purpose was the forecast crude oil prices. The data
was time dependent therefore, the data had to be differenced in order for diagnostics and forecasting purposes. The diagnostics
process revealed that the AR of order 1 and the MA of order 2 were the most optimal in terms of forecasting. This was determined by 
plotting the partial auto correlations and using the Baynesian Information Criteria. The two models were combined and it was discovered 
that the combined models had lower residual sum of squares than the individual respective models. The data was then split into training and
testing sets and the ARIMA model, with the respective orders, was trained. The trained model was used to forecast and the predicted values 
were plotted along with the observed values. The average error was caluculed to be 6.09% on the test set. 
