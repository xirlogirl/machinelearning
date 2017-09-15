# Applied Machine Learning in Python Week 2

## Supervised Learning Algorithms

This week discussed multi-class classification problems, overfitting and underfitting in regression and classification problems and the use of the R^2 metric, the coefficient of determination (0 is a constant model that predicts the mean always, 1 is a perfect predictor) for the assessment of regression models. Regularization - the penalty for large variations in fit parameters, was also discussed at length, in particular Lasso (L1 regularization) and Ridge regression.

Algorithms for regression problems - `KNeighborsRegressor` and `LinearRegression` in sklearn were demonstrated with this week's jupyter notebook. Feature normalization (eg. mean normalization and minmaxscaling) was discussed, in particular their importance with respect to learning algorithms that require a Euclidean distance for fitting. 

Logistic Regression was introduced for solving binary classification problems.
Support Vector Machines were explained and demonstrated - in particular the C and gamma parameters. The radial basis function kernel was demonstrated and its shape for different gamma values.

Cross Validation (n-fold) was explained and demonstrated in sklearn.

Part I of this weeks assignment required the student to implement a linear regressor on some made up data with random noise, and use a polynomial regressor on sinusoidal data with random noise. The R^2 had to be evaluated for each and from the scores to determine if the algorithm had underfit or overfit the data. Next, ridge and lasso regularization was employed.

Part II of this weeks assigment focused on classification problems; specifically whether or not a mushroom was poisonous based on its features. A decision tree classifier was used, in particular the very useful `feature_importances_` attribute was used to determine the best predictors of the label class. Support Vector Classifiers were then used on the same dataset, and the iterating over different gamma and C  and the effect on accuracy, in particular when the model achieves its best fit without under/overfitting. 
