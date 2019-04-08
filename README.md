# House-price-prediction-using-linear-regression
This file builds a model to predict house prices for a house given various aspects of the house such as its area,	number of bedrooms	and bathrooms, number of	stories, whether the house is located on the mainroad etc.
After pre-processing the data by adding new features, modifying existing features etc., the data is normalized using min-max scaling.
SkLearn's RFE module is used for recursive feature elimination, thereby retaining only independent features.
Further, a custom function is developed for calculating variance inflation factor (VIF) to visualise dependence amongst different features.
Finally, the data is split into training and test data and SkLearn's LinearRegression module is used to fit a linear model on the training data. The model is then tested on the test data and the predicted and actual values of house prices of the test data are plotted for better visualisation along with a plot of error terms.
