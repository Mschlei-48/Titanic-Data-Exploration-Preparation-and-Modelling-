# Titanic-Data-Exploration-Preparation-and-Modelling-

## Project Overview

* The famous Titanic dataset was used for exploration,preparation and modelling with Logistic Regression model.
* Four feature selction techniques were used to select the best features to include in the model, namely :
   1. RFE(Recursive Feature Elimination)
   2. Decision Trees Feature Selection
   3. Correlation Analysis
   4. Coefficient Feature Importance(Using Logistic Regression)
* The model obtained an accuracy of 100% using pre-processing required by Logistic Regression, which included :
    1. Removing outliers.
    2. Removing mutlicollinearity - The model asssumees that the feature variables are not correlated with each other. Highly correlated features should be removed.
    3. Asserting linear assumption - Feature variables need to have a linear relationship with the target variable. A log transformation is used to assert that relationship if it is not present.
    4. Asserting normal distribution - Feature variables need to hae a normal distribution. If they are not normally distributed a log transform or BoxCox is used to assert the distribution.
    5. Feature scaling - The features must be scaled as they might not be habing the same range of values, therefore redulting in features with high numbers dominating the model and appearing to be more important than other variables. Feature scaling helps us scale them to the same range and tehrefore give each feature a chance to equally contribute to the model.
  
  
  ## Sample Figures from Exploratory Data Analysis and Data Preparation
  
    
    
    
![SampleImage](https://user-images.githubusercontent.com/83508295/194419701-b4ee71d0-98db-4038-9721-fce4f6a681c3.png)
![Figure6](https://user-images.githubusercontent.com/83508295/194419729-0c793e66-2c98-41e9-8506-06345500d5ec.png)
![Figure2](https://user-images.githubusercontent.com/83508295/194419799-fd19b9c2-bec2-4f17-bde5-a092cce9174c.png)


## Model Classification Report
![ClassificataionReport](https://user-images.githubusercontent.com/83508295/194420563-9ea7a564-a9af-459c-9550-a7a20fada78c.jpeg)

