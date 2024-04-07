
# Stock Price Prediction
This project is about predicting stock prices using machine learning models. The dataset used in this project is the historical stock prices of Tesla (TSLA), which is publicly available.

## Project Description
The goal of this project is to predict whether the stock price of Tesla will increase or decrease. The prediction is based on historical stock price data and various features derived from this data.

## Data
The data used in this project is the historical stock prices of Tesla (TSLA). The data includes the following columns:

- Open: The opening price of the stock on a particular day.
- High: The highest price of the stock on a particular day.
- Low: The lowest price of the stock on a particular day.
- Close: The closing price of the stock on a particular day.
- Volume: The number of shares traded on a particular day.

## Methodology
The project involves several steps:

## Data Loading and Preprocessing: 
The data is loaded using pandas and preprocessed. The preprocessing steps include dropping unnecessary columns, handling missing values, and creating new features.

## Exploratory Data Analysis (EDA): 
EDA is performed to understand the distribution of the data and the relationship between different features. This includes creating distribution plots and box plots and calculating correlation between features.

## Feature Engineering: 
New features are created based on the existing features. These new features include ‘open-close’ (difference between opening and closing price), ‘low-high’ (difference between lowest and highest price), and ‘is_quarter_end’ (whether the month is the end of a quarter).

## Model Training: 
Three different machine learning models are trained on the data: Logistic Regression, Support Vector Classifier (SVC), and XGBoost Classifier.

## Model Evaluation: 
The models are evaluated based on their accuracy score. The model with the highest accuracy score is selected as the final model.

## Results
The Logistic Regression model achieved the highest accuracy of 60.33%.

## Usage
To run the project, you need to have Python installed on your machine. You also need to install the necessary libraries, which include numpy, pandas, matplotlib, seaborn, sklearn, and xgboost.

You can run the project by executing the Python script in a Python environment.

## Contributing
Contributions are welcome. Please feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
This project is licensed under the MIT License. See the LICENSE file for details.
