# Time Series - Resampling Data

### The company name is Sweet Lift Taxi

The company needs to attract more drivers during peak hours,  the mission is to predict the amount of taxi orders for the next hour. Build a model for such a prediction.
. 
 
### Details of Time series

EDA, Resampled the data.  Feature engineered the time spacing features. Function creation to plot different time intervals.  Create correlation matrix. Used statsmodel framework (decomposed, for periodic framework).  Create RMSE function for accuracy metric.  Build model using Gridsearch framework.


#### The Data

Dataset provides number of orders and a timestamp.   


### Results

Compiled the data in to details based on accumulated hourly action.  Observed the days and weeks based on hours.  Approximately 9pm until 1 am are busiest.  Weekends are busier.  From 5am to 7am ride request are much slower. Final evaluation on test set; with Catboost model presenting lowest RMSE; also extends a longer run time. 
