# JSC370 Final Project: Most Predictive Risk Factors of Type 2 Diabetes and Make Predictions

# Links
[Website]()
[Report](Report.pdf)
[Data]()

# Abstract

### Objectives

Diabetes is a serious chronic disease all over the world. The global prevalence of diabetes continues to skyrocket, exacerbated by a lack of awareness of the disease. For long, researchers have been focused on examining the diabetes risks and predicting diabetes in the early stage. Therefore, this project analyzes on the cause of type 2 diabetes and make predictions of diabetes given the information provided in the Behavioral Risk Factor Surveillance System (BRFSS) survey data.

### Methods

Firstly, the data is cleaned by selecting the columns of interest, standardizing the values, and removing the missing values.

Secondly, exploratory data analysis is performed, including boxplots of numerical variables, and a contingency table and proportional barplots of categorical variables. From the patterns of the variables, some data preprocessing may be performed.

Thirdly, split the dataset into training (70%) and testing (30%). Machine learning models such as logistic regression model, classification trees, bagging, random forests, boosting, and extreme gradient boosting are fitted on the training dataset that is splitted.

Lastly, the performances of all models on the test data are evaluated and compared. The best prediction model is selected and the most important predictors are inferred.

### Conclusions

The best model among all the models fitted is the boosting, which has a test accuracy of 76.30% and test MSE of 0.1596.

The important predictors selected by the models are `race`, `age`, `bmi`, `health`, and `education`, which indicates that they may be the most predictive risk factors of `diabetes`.