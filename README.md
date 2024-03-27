# 🚗 Predicting Used Car Prices in the Indian Market Using Machine Learning Techniques
### [Heroku Deployment link](https://usedcar-prediction-ineuron.herokuapp.com/)

This project aims to solve the problem of predicting the price of a used car, using Sklearn's supervised machine learning techniques. It is a regression problem and predictions are carried out on dataset of used car sales in the Indian car market Cardheko website. Several regression techniques have been studied, including XGboost and Random forests of decision trees.


## Models Used
* Linear Regression
* Lasso Regression
* Ridge Regression
* K-Neighbors Regressor
* Decision Tree
* Random Forest Regressor
* XGBRegressor
* CatBoosting Regressor
* AdaBoost Regressor

From these above models after hyperparameter optimization we selected Top two models which were XGBRegressor and Random Forest Regressors and used the following in Pipeline.

* GridSearchCV is used for Hyperparameter Optimization in the pipeline.

**Components** : Contains all components of Machine Learning Project
- DataIngestion
- DataValidation
- DataTransformations
- ModelTrainer
- ModelEvaluation
- ModelPusher

## Conclusion
- This Project can be used in real-life by Users or Used car dealers to predict the Estimated Price of the car based on input specifications.
