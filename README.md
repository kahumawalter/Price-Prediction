# Price Prediction

There are 53,940 diamonds in the dataset with 10 features (carat, cut, color, clarity, depth, table, price, x, y, and z). Most variables are numeric in nature, but the variables cut, color, and clarity are ordered factor variables. 

I make predictions to the price using regression models like Random Forest Regressor, Linear Regression and Decision Tree Regressor. After seeing the results of all the models, it was evident that the Random Forest Regressor out performed the rest with a score 98% accuracy on the test data. 

# Visualization
To get a better understanding of the data, I used the heat map visualization to see which features were highly correlated. 


There is a strong correlation between my target 'Price' and features like carat, x,y and z. This explains that these play a big factor in the price evaluation.
