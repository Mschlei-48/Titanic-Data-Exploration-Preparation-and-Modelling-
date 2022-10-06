# Titanic-Data-Exploration-Preparation-and-Modelling-

* The famous Titanic dataset was used for exploration,preparation and modelling with Logistic Regression model.
* The model obtained an accuracy of 100% using pre-processing required by Logistic Regression, which included :
    1. Removing outliers.
    2. Removing mutlicollinearity - The model asssumees that the feature variables are not correlated with each other. Highly correlated features should be removed.
    3. Asserting linear assumption - Feature variables need to have a linear relationship with the target variable. A log transformation is used to assert that relationship if it is not present.
    4. Asserting normal distribution - Feature variables need to hae a normal distribution. If they are not normally distributed a log transform or BoxCox is used to assert the distribution.
    5. Feature scaling - The features must be scaled as they might not be habing the same range of values, therefore redulting in features with high numbers dominating the model and appearing to be more important than other variables. Feature scaling helps us scale them to the same range and tehrefore give each feature a chance to equally contribute to the model.
    
    
    
