# PRODIGY_ML_01

## House Price Prediction using Linear Regression
### Project Overview\

#### This project aims to predict house prices using a linear regression model. The model uses features such as the number of bathrooms, bedrooms, and the total square footage of the house.

#### Dataset
The dataset used in this project consists of house sale prices for various houses along with associated house features. The dataset is split into a training set (train.csv) and a test set (test.csv). The training set is used to train the model, and the test set is used to evaluate the model’s performance.

#### Features
The features used in this project are:
HalfBath: Half bathrooms in the house
FullBath: Full bathrooms in the house
BsmtHalfBath: Half bathrooms in the basement
BsmtFullBath: Full bathrooms in the basement
BedroomAbvGr: Bedrooms above ground
LotArea: Lot size in square feet

#### Target Variable
The target variable is SalePrice, which represents the price at which the house was sold.

#### Model
The model used in this project is a Linear Regression model from the sklearn.linear_model library.

##### Usage
Load the datasets using pandas.
Select the relevant features and remove any rows with missing values.
Separate the features and the target variable in the training set.
Train the Linear Regression model on the training set.
Make predictions on the test set using the trained model.
Save the predictions to a CSV file.

#### Dependencies
Python
pandas
numpy
sklearn
