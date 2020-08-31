# time_series-a_yen_for_the_future





## Linear Regression
![Predictions](Images/returns_graph.png)

Utilizing a regression model based on X and y training data and applying it to 
X testing data, there does not appear to be much correlation between predicted 
and actual returns over the next 20 trading days.  Each major peak appears to
go in opposite directions.  Furthermore, the actual returns vary from about 
-0.5% to 1%, while the predicted returns' range is much smaller--0.015% to 
-0.005%.  This range could indicate a more conservative projection.


### In-Sample Performance
![in_sample](Images/in_sample_error.png)


### Out-of-Sample Performance
![in_sample](Images/out_of_sample_error.png)


Overall, this model appears to perform better with out-of-sample data compared
to in-sample data, although there is enough error in both cases to make one 
skeptical of its overall effectiveness.  Out-of-sample mean squared error 
(0.171 to to 0.498) and root mean squared error (0.414 to 0.706) were both lower
than in-sample readings.  By this measure the model may do a better job of 
predicting out-of-sample prices comparatively, but the size of the error makes
me hesitant to solely rely on this model to predict future prices.