# kn_car_prices
Uses KNeighborsRegressor to predict car prices

We will use various attributes of individual cars and their known sale prices to produce a k-nearest neighbors model. 
The KN model will then attempt to predict sales prices of cars with similar attributes. 

The car sales prices are assumed to be continuous which is why the KNeighborsRegressor is used instead of the KNeighborsClassifier - 
the latter being more suitable for predicting category classifications.
