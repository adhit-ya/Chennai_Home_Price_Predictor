

🚀 Chennai House Price Predictor

📍 Overview:

Developed a machine learning model to accurately predict house prices in Chennai, India. Leveraging features like age, BHK (Bedrooms, Halls, and Kitchens), area, bathroom and location, the model provides reliable predictions for potential buyers, sellers, and real estate investors.

💡 Key Highlights:

Exploratory Data Analysis (EDA):

Removed unnecessary columns, including the builder's name and home construction status.
Addressed skewness in data using the transformation log(x+1).
Handled missing values by filling them with the median for skewed features like age and BHK.
Data Preprocessing:

Scaled key features: price, age, area, bathroom and BHK.
Encoded the categorical location feature using one-hot encoding for better model compatibility.
Modeling and Performance:

Split the dataset into 80% training and 20% testing data.
Built and compared two models:
Linear Regression
Random Forest Regressor (achieved an impressive score of 0.9180193774937256).

📊 Dataset:
Sourced from Kaggle, the dataset contains 2620 rows of relevant features contributing to house price prediction.

🔧 Tech Stack:

Python, Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn

🌟 Impact:
This project demonstrates a robust approach to predictive modeling in the real estate domain and highlights the importance of data preprocessing, EDA, and feature engineering.
