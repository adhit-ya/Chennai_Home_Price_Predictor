
Chennai House Price Predictor.
This repository contains a machine learning model designed to predict house prices in Chennai, India. The model utilizes features such as age, BHK (Bedrooms, Halls, and Kitchens), area, and location to make predictions. The dataset, consisting of 2620 rows, was sourced from Kaggle.

Key Features

Exploratory Data Analysis (EDA):

Removed irrelevant columns like the builder's name and the construction status of the home.
Checked for skewed data and rectified it using the transformation log(x+1).
Handled null values by filling them with the median (suitable for left-skewed distributions like age and BHK).

Data Preprocessing:

Scaled numerical features such as price, age, area, and BHK.
Encoded the categorical feature location using one-hot encoding (get_dummies).

Modeling:

Split the dataset into 80% training data and 20% testing data.

Built and compared two regression models:

Linear Regression
Random Forest Regressor

Result:

Random Forest Regressor achieved a score of 0.922243, outperforming Linear Regression.
