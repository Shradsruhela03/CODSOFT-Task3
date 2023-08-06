# CODSOFT-Task3 Sales Prediction using Python
Name:shraddha ruhela
Batch:july
Domain:Data Science
Aim:
The aim of this project is to predict sales based on advertising expenditure using the given dataset. The dataset contains information about advertising spending on different platforms (TV, Radio, and Newspaper) and the corresponding sales amount.
# libraries used

The following important libraries were used for this project:
1-pandas
2-matplotlib.pyplot
3-seaborn
4-sklearn.model_selection.train_test_split
5-sklearn.linear_model.LinearRegression
6-numpy

# Dataset
The dataset was loaded using pandas as a DataFrame from the file "advertising.csv".

# Model Training
The data was split into training and testing sets using train_test_split.
Linear regression model was trained on the training data using sklearn.linear_model.LinearRegression.

# Model Prediction
The model was used to predict sales based on advertising expenditure on TV for the test set using model.predict(X_test) and the corresponding advertising expenditure on TV in the test set.
The model coefficients and intercept were obtained using model.coef_ and model.intercept_.
The predictions and actual sales values were plotted using matplotlib.pyplot.plot and matplotlib.pyplot.scatter.
