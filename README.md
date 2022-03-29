ML SUPERVISED -REGRESSION

bike sharing demand prediction

The contents of the data came from a city called Seoul. A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.The data had variables such as date, hour, temperature, humidity, wind-speed, visibility, dew point temperature, solar radiation, rainfall, snowfall, seasons, holiday, functioning day and rented bike count.The problem statement was to build a machine learning model that could predict the rented bikes count required for an hour, given other variables

here, I started with loading the dataset ,performing EDA and implemented various regression algorithms like linear regression,random forest,decision tree regressor,gradient boosting and SVR. among the algorithms random forest regressor  and gradient boosting performs well with tuning some of the hyperparameters and evaluated the model performance by calculating the R2 and adjusted R2

conclusion

Hour of the day holds most importance among all the features for prediction of dataset
It is observed that highest number bike rentals counts in Autumn/fall Summer Seasons and the lowest in Spring season.
 We observed that the highest number of bike rentals on a clear day and the lowest on a snowy or rainy day
As we can see the top 5 important features of our dataset are: Season_winter, Temperature, Hour, Season_autumn, Humidity
Peoples dont use rented bikes in no functioning day
 people tend to rent bikes when the temperature is between -5 to 25 degrees
  people tend to rent bikes when the visibility is between 300 to 1700
for all the above experiments we can conclude that gradient boosting  and random forest regressor with using hyperparameters we got the best results
The model performed well in this case but as the data is time dependent, values of temperature, wind-speed, solar radiation etc. will not always be consistent. Therefore, there will be scenarios where the model might not perform well. As Machine learning is an exponentially evolving field, we will have to be prepared for all contingencies and also keep checking our model from time to time
 

