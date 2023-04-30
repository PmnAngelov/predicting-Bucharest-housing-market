# Predicting the Bucharest Housing Market - Personal Project
Analyzing and predicting the prices of the housing market in Bucharest, Romania.

## Project Overview
This project uses machine learning techniques to predict apartment prices in Bucharest, Romania. The main source of the database is represented by www.imobiliare.ro, which is one of the most popular real estate websites in Romania. 

The project consists of the following components:

### 1. **Data Cleaning and Preprocessing**
* Importing the needed libraries and loading the dataset using Pandas
* Exploring the features and data types
* Checking for missing values, renaming columns and transforming the data types
* Calculating and adding a column for price ranges

### 2. **Exploratory Data Analysis** 
* Basic summary statistics and information about the data
* Visualizing the distribution and skewness of the different variables
* Analyzing the correlation between the features and the target variable
* Identify any interesting patterns or trends in the data

### 3. **Data Preparation For Machine Learning**
* Transforming the data into a format suitable for machine learning models
* Encoding categorical variables
* Standardising the data's numerical features
* Splitting the data into a training set of 80% and a testing set of 20%

### 4. **Training Models and Evaluation**
* Several regression models are selected using Scikit-learn to predict aparment prices
* The models are trained on the training data
* Their performance is evaluated on the testing data and metrics such as MSE, RMSE and R-squared.
* The best-performing model is selected and and it's predictions are analyzed

## Dependencies 
This project uses the following Python libraries:
* **NumPy**: for numerical computations
* **Pandas**: for data manipulation and analysis
* **Matplotlib**: for data visualization
* **Seaborn**: for data visualization
* **Scikit-learn**: for machine learning modeling

## Conclusion
The project demonstrates how statistical analysis and machine learning models can be used to predict real estate prices based on different features. The project also shows the importance of data cleaning, preprocessing and visual analysis in preparing data for machine learning models and gaining valuable insights from it.
