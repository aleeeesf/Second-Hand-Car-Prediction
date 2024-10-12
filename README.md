# Used Cars Price Prediction - Machine Learning Project

This project applies regression algorithms to predict the price of used cars using a dataset with various features. The aim of this notebook is to serve as an introduction to regression by applying different techniques and models.

## Dataset Description

The dataset contains information about second-hand cars, including features such as:

- **v.id**: Vehicle ID
- **on road old**: Original price of the car
- **on road now**: Current price of the car
- **years**: Age of the car in years
- **km**: Kilometers driven
- **rating**: Car rating
- **condition**: General condition of the car
- **economy**: Fuel efficiency
- **top speed**: Maximum speed
- **hp**: Horsepower
- **torque**: Torque
- **current price**: Current second-hand price (the target variable)

## Project Structure

The notebook follows these steps:

1. **Data Exploration**: Perform exploratory data analysis to understand the distribution of variables and their relationship with the price.
2. **Preprocessing**: Normalize and scale the data to improve model performance.
3. **Model Training**:
    - **Neural Network** with TensorFlow
    - **XGBoost**
    - **Linear Regression** with Scikit-learn
4. **Evaluation**: Evaluate the models using metrics such as Mean Absolute Error (MAE) and Mean Squared Error (MSE).

## Main Libraries Used

- **TensorFlow**: For creating and training the neural network.
- **XGBoost**: An efficient boosting algorithm for regression tasks.
- **Scikit-learn**: For linear regression and cross-validation.
- **Pandas and Numpy**: For data manipulation.
- **Matplotlib and Seaborn**: For data visualization.

## Results

The Neural Network built with TensorFlow achieved the lowest error, outperforming both XGBoost and Linear Regression models.

## Installation

To run this project, you will need to install the following dependencies:

```bash
pip install numpy pandas seaborn xgboost tensorflow scikit-learn matplotlib
