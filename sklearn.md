- Every algorithm is exposed in scikit-learn via an "Estimator".
- First, import the model: from sklearn.family import Model
  - Ex: from sklearn.linear_model import LinearRegression

Estimator parameters: All parameters of an estimator can be set when instantiated and have suitable default values.
- Ex: 
  - model = LinearRegression(normalize=True)
  - LinearRegression(copy_X=True, fit_intercept=True, normalize=True)
