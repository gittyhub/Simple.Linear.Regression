# Simple.Linear.Regression

Simple linear regression example from TowardsDataScience.com
<br>
https://towardsdatascience.com/machine-learning-basics-simple-linear-regression-bc83c01baa07

1)Get our data set
2)What is the dependent variable (y=salary) what is the independent variable (x=Years Experience)
a)Split data using scklean trains_test_split function. X_train, X_test, y_train, y_test = train_test_split(X, y, test_size = 0.3)
b.The training set will be used to train the model, and the test set will be use to test the model after it has been trained
c.Set test size. Seting how much of the independent data will be used for test.
d.Assign a variable (r) to LinearRegression from sklearn (r = LinearRegression())
e.Fit the variable to the training set (r.fit(X_train, y_train))
f.When the model has been fitted with the training data, we see the predicted values using regress.predict(X_test)
