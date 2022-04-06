# **Top 12% Solution**
 
 House Prices - Advanced Regression Techniques

# The goal of this project:
Is to predict the sales price of each house from a neighborhood in Ames, Iowa.

# Why would a company benefit from this project and will there be a next step to this project:
1.  A company such as Zillow or any real estate company would benefit from this by being able to see how prices for each house are predicted. 
2. If needed the companies can ask to add more onto this dataset to try and predict other type of homes in a different area or even try to calculate monthly rental prices.

# How to find the best tree model: 
I used XGBOOSTRegressor because it has highly efficient implementation.

# Why did I use this parameters: 
I used learning_rate to prevent any over fitting of the data.

# How would I implement this algorithm: 
After going through and prepping the data such as removing and modify the nulls, adding a few features, and predicting the final model with XGBoost.

# My results: 
After predicting the model the final mean squared error value that was predicted is 199500 per house.

# Why is this Regression: 
This is a Regression project because we are predicting the house prices which are continuous. 
