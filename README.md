# uk-airbnb

## Linear Regression
* ran a linear regression to predict the price of an airbnb
*	output = 'price'
* 	preds = 'latitude','longitude','minimum_nights','number_of_reviews','calculated_host_listings_count','availability_365','number_of_reviews_ltm'
* performed a 20/80 tts

## Model Performance
* evaluated the model using r2, mse, and mae on the train and test set
* train r2 = 0.11567354765550197
* test r2 = 0.0866632158186702
	* test r2 < train r2; therefore the model does not generalize well on the data (under-fit)
* mse = 211348.3688261384
	* high mse; optimal to score close to 0.0 -> how close the regression line is to data points
* mae = 128.46428352946

## Coefficients interpretation

