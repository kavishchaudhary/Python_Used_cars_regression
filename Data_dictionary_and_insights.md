Source: https://zenodo.org/record/6438518

Dataset that contains information on the different second-hand cars that were for sale on the www.flexicar.es website for the province of Barcelona as of April 8, 2022.

790 cars are included in the dataset, being the cars that were for sale on the Flexicar website for the province of Barcelona at the time of extraction, described by the following attributes:


Data Dictionary

•	brand - car brand

•	model - car model

•	price - car price

•	engine - car engine

•	year - production year

•	mileage - car mileage

•	fuel - fuel type

•	gearbox - gearbox type

•	location - car location



INSIGHTS

•	year(predictor)- This variable is normally distributed.

•	No null values in the dataset.

•	No outliers detected using isolation forest.

•	The fuel predictor is skewed towards 2 major categories – diesel and gasoline.

•	The gearbox predictor is skewed towards manual class.

•	The location predictor seems to be uniformly distributed.

•	The mileage variable is normally distributed.

•	The target variable is right skewed.

•	The best model is the BaggingRegressor which gives the minimum RMSE.

