# HousePricePridiction
         PIPELINES
Collection of Data - Data collection is needed before any kind of machine learning research is carried out. Dataset validity is a must otherwise there is no point in analysing the data.

Data Preprocessing  - Data preprocessing is the process of cleaning our data set. There might be missing values or outliers in the dataset. These can be handled by data cleaning. If there are many missing values in a variable we will drop those values or substitute it with the average value.

Training the Model - Since the data is broken down into two modules: a Training set and Test set, we must initially train the model. The training set includes the target variable. Various regression algorithms are applied to the training data set. Some of them are Random Forest Regressor, Gradient Boost Regressor, SGDRegressor, XGB Regressor.

Testing - The trained model is applied to test the dataset and house prices are predicted.

			METHODOLOGY
Exploratory Data Analysis - By conducting exploratory data analysis we obtain a better understanding of the data which can be helpful for handling the values and building the different regression models.our main aim in EDA was,
Look into the relationship between each variable and sale price distribution, and identify any patterns. For example, what is the range of most occurred prices and how it is related to the other features of the dataset.
We will also analyse relationships between the features. This may reveal that certain features are redundant and this would help the subsequent analysis

Feature Selection - It helps to gain more information about data, eliminate the noise from the data, handle the missingNull(NA) values, handle non-numerical features and create a more noise-less dataset which can be helpful to avoid overfitting and to be better for an accurate regression model. In this section we analysed,
Price and probability distribution of sale prices of houses.
Unique values in each attributes
No of occurence of each value in each non-numerical attribute.
Distribution of values in numerical attributes.
Eliminate columns like utilities,alley,PoolQc due to higher number of missing values.
Created some new columns like YrBuildandRemod using YearBuild and YearRemod to get some more features which may be impacting the house prices.
Encode non-numerical values with some numerical values and then applied 
Used logs and squares the further encode the encoded data

Modelling - In this section we used the following regression models to create models and simultaneously use R-squad and mean_absolute_error to check the efficiency of the model..
Linear Regression
Random Forest Regression
XGB Regression
Gradient Boost Regression
SGD Regression

Exploration of reasons for misclassification in model - In this section we analysed the results and then go back to original results to find out why some values are misclassified and how we can make our models more accurate.

