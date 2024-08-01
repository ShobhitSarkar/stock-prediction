# stock-prediction

### Project Overview

This project aims to predict stock prices using historical data. The focus is on creating a model that can predict the closing prices of stocks, which is crucial for making informed trading decisions. The project leverages machine learning techniques, specifically Long Short-Term Memory (LSTM) networks, to model the time series data of stock prices.

### Technologies Used

- **Python**: Programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **TensorFlow**: Deep learning framework
- **Scikit-learn**: Machine learning library
- **Jupyter Notebook**: Interactive computing environment

### Project Workflow

#### Data Loading and Preparation

The dataset is loaded and preprocessed to prepare it for training the model.

#### Data Cleaning and Visualization

The dataset is filtered for a specific ticker, unnecessary columns are dropped, and the date is converted to a datetime object. The closing prices are then plotted to visualize the stock's behavior.

#### Moving Averages

Plotting moving averages to observe trends and smooth out short-term fluctuations.

#### Data Preprocessing for Model

Data is scaled and split into training, validation, and test sets.

### Model Building and Training

An LSTM model is built and trained on the prepared data.

### Model Evaluation

Evaluate the model's performance on the validation and test sets.

### Some of the terms used in this project:

- **Ticker**: A unique symbol assigned to a publicly traded company.
- **Close Price**: The final price at which a stock is traded on a given trading day.
- **Moving Average (MA)**: A statistical calculation used to analyze data points by creating a series of averages of different subsets of the full data set. In finance, moving averages are often used to smooth out price data to identify trends.
- **Mean Squared Error (MSE)**: A measure of the average of the squares of the errors—that is, the average squared difference between the estimated values and what is estimated.
- **Mean Absolute Error (MAE)**: A measure of errors between paired observations expressing the same phenomenon. It is the average of the absolute errors.
- **R-squared (R²)**: A statistical measure that represents the proportion of the variance for a dependent variable that's explained by an independent variable or variables in a regression model.

### Author Information

This project was developed by Shobhit Sarkar. For more information, you can reach out via email at [shobhitsarkar0802@gmail.com]. Always open to collaborations and questions ! 
