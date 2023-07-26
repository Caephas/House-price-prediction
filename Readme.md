### House Price Prediction using Machine Learning
This project aims to build a machine learning model to predict house prices based on various features, using the California housing dataset. The model implemented in this project is the XGBoost Regressor from the XGBoost library.

Project Structure
```
.
├── README.md
├── housing_price_prediction.ipynb

```

## Dataset
The dataset used in this project is the California housing dataset, which is inbuilt in the sklearn library.

## Dependencies
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
XGBoost

## Implementation
The project follows these steps:

1. Importing the required libraries.
2. Importing the California housing dataset.
3. Loading the dataset into a pandas DataFrame.
4. Checking the number of rows and columns in the DataFrame, and performing basic data analysis.
5. Understanding the correlation between various features in the dataset.
6. Splitting the data into input features (X) and the target feature (Y), which is 'price'.
7. Splitting the data into training and testing sets.
8. Training the XGBoost Regressor model on the training data.
9. Making predictions on the training data and evaluating the model.
10. Making predictions on the test data and visualizing the predicted vs actual prices.

## Usage

Clone this repository to your local machine.
Install the required dependencies.
Open the Jupyter notebook: housing_price_prediction.ipynb.
Run all cells in the notebook to train and evaluate the model.
This notebook can be opened and executed in environments such as Google Colab, Jupyter Notebook, or Visual Studio Code which supports .ipynb files. It cannot be run directly from the terminal as it is in a Jupyter Notebook format.

## Results
The model's performance is evaluated using R squared error and Mean Absolute Error on both training and testing data. Finally, a scatter plot visualizing the actual prices vs predicted prices is provided