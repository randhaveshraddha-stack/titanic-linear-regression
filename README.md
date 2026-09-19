# Titanic Passenger Fare Prediction Using Linear Regression

## Project Overview

This project uses Machine Learning to predict the fare paid by passengers on the Titanic dataset using Linear Regression.

## Objective

The objective of this project is to predict passenger fare using passenger-related features.

## Dataset

The dataset used in this project is the Titanic dataset from Kaggle.

The dataset contains information about Titanic passengers, including:

- Passenger Class
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Fare

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithm

**Linear Regression**

### Input Features

- Pclass
- Age
- SibSp
- Parch

### Target Variable

- Fare

## Data Preprocessing

Missing values in the Age column were handled using the median age.

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Visualization

The project includes an Actual vs Predicted Fare visualization to compare the model predictions with the actual fare values.

## Conclusion

The Linear Regression model was able to learn a relationship between passenger characteristics and passenger fare. However, the selected features do not completely explain the variation in fare, suggesting that additional features could improve the model.

## Author

Shraddha
