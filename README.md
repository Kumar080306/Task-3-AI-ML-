# Task-No.3
Housing Data Analysis and Model Training

Overview

This project demonstrates the process of loading, cleaning, transforming, training, and evaluating a machine learning model on a housing dataset. The project focuses on linear regression to predict house prices based on various features like area, number of rooms, etc. The final model is saved, and users can download it in CSV format with a custom name.

Steps

1. Dataset Loading
The project begins by loading a housing dataset from a CSV file (Housing.csv). The dataset contains information about housing prices and features such as area, number of rooms, etc.

2. Data Preprocessing
We perform various preprocessing steps, including:

Handling missing data: Ensuring no missing values exist in the dataset.
Feature encoding: Converting categorical variables into numeric representations.
Feature selection: Splitting the dataset into features (X) and target (y).
3. Model Training
We use Linear Regression from sklearn to train the model on the preprocessed dataset. The model is then evaluated using common metrics:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² (Coefficient of Determination)
4. Model Evaluation
We evaluate the trained model on a separate test set and print out the performance metrics.

5. File Renaming and Download
After making updates to the dataset, we save the changes to a new file. We also allow the user to download the updated dataset or model file with a custom name.
