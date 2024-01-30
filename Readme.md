# California House Price Prediction Notebook

## Overview

This README provides a comprehensive overview of the California House Price Prediction notebook, which employs various Python libraries and machine learning techniques to predict house prices based on the California housing dataset.

### Dependencies

The notebook uses the following Python libraries:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- MLflow
- Scikit-Learn
- XGBoost
- Requests

### Dataset

The California housing dataset is used, which includes data on house prices and other related features.

### Workflow

1. **Data Import**: The notebook begins by importing the necessary Python libraries and the California housing dataset.

2. **Data Exploration and Preprocessing**:
    - Load the data into a Pandas DataFrame.
    - Perform initial data exploration, including checking for null values and understanding the data structure.
    - Visualize the correlations between different features using a heatmap.

3. **Data Splitting**: The dataset is split into training and testing sets.

4. **Model Training**:
    - An XGBoost Regressor model is trained on the data.
    - MLflow is integrated for experiment tracking and model management.
    - The model's performance is evaluated using metrics like mean squared error, mean absolute error, and R-squared.

5. **Model Evaluation**:
    - The model's predictions are compared against the actual prices for both training and testing datasets.
    - A scatter plot is used to visualize the actual vs. predicted prices.

6. **Model Persistence**:
    - The trained model is saved using MLflow.
    - Instructions are provided for loading and querying the saved model.

7. **Model Deployment and Querying**:
    - The notebook demonstrates how to serve the model locally and query it via a REST API.
    - Additionally, it shows how to deploy the model to a cloud platform (GCP) and perform remote querying.

### MLflow Integration

- MLflow is used for experiment tracking, model logging, and model management.
- The notebook demonstrates how to log metrics and models to MLflow and retrieve them for later use or deployment.
- [End-to-End Guide to ML Model Lifecycle: From MLflow Integration to Cloud Deployment](https://www.notion.so/End-to-End-Guide-to-ML-Model-Lifecycle-From-MLflow-Integration-to-Cloud-Deployment-9b00a04d71334e37bfe9924b5f0d1b9a?pvs=4)

### Conclusion

This notebook provides a comprehensive guide to predicting California house prices using machine learning techniques, with a focus on XGBoost and MLflow for model training and management.
