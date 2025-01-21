#Bengaluru House Price Prediction Using Linear Regression
Description
This project focuses on predicting house prices in Bengaluru using a Linear Regression model. Real estate prices are influenced by various factors such as location, area type, and number of bedrooms. By analyzing historical data, this model provides insights into key factors driving property prices and helps predict prices for new properties.

The implementation is done entirely in Python within a Jupyter Notebook. The dataset used in this project contains features such as location, area type, total square footage, and number of bathrooms, making it ideal for regression-based modeling.

This project demonstrates the process of data preprocessing, exploratory data analysis, and the application of a regression algorithm to solve a real-world problem.

#Dataset
The dataset contains the following features:

Area Type: Type of the area (e.g., Built-up Area, Super Built-up Area).
Availability: Status of the property (e.g., Ready to Move).
Location: Location of the property within Bengaluru.
Price: Target variable, price of the house (in rupees).
Total Sqft: Total area in square feet.
Size: Number of bedrooms (e.g., 2 BHK, 3 BHK).
Bath: Number of bathrooms.
Balcony: Number of balconies.

#Project Overview
Data Preprocessing:

Handle missing or invalid values.
Apply dummy encoding for categorical features like Area Type.
Exploratory Data Analysis (EDA):

Visualize the distribution of key features.
Identify correlations between variables like Total Sqft, Bath, and Price.
Model Development:

Split the dataset into training and testing sets.
Train a Linear Regression model to predict house prices.
Model Evaluation:

Evaluate the model’s performance using metrics such as R² Score and Mean Absolute Error (MAE).

#Requirements
Install the following libraries to run the project:

NumPy
Pandas
Matplotlib
Seaborn
scikit-learn
