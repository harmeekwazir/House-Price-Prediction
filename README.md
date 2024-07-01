This notebook explores the housing dataset from [Kaggle](https://www.kaggle.com/c/home-data-for-ml-course/overview).
The dataset contains 79 variables describing various aspects of residential homes in Ames, Iowa. The data has been separated into training and test sets. The goal is to predict the final Sale Price of the houses in the test data set. 

Advanced feature engineering is used to infer missing values in the data set. The categorical features are transformed into numerical features using one hot encoding. 
The performances of various regression techniques such as Random Forest, Stochastic Gradient Descent, Gradient Boosting, and Xtremme Gradient Boosting are compared. Using the best fit model, I got a score of 0.13472 in the Kaggle competition.
