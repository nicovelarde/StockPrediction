# Stock Prediction

This is a simple Python application that uses Streamlit, a web application framework, along with Keras to predict the stock price trend of a given stock ticker. The application fetches historical stock data using the Yahoo Finance API, preprocesses the data, and then uses a pre-trained Keras model to make predictions.

Prerequisites
------------------
* Python 3.x
*  Streamlit
*  Keras
*  pandas_datareader
*  yfinance
*  numpy
*  scikit-learn

Installation
------------------

Clone or download this repository to your local machine.<br>
Install the required dependencies by running: pip install streamlit keras pandas_datareader yfinance numpy scikit-learn.

Usage
------------------
Make sure you have the 'keras_model.h5' file containing the pre-trained Keras model in the same directory as the code. If you don't have a pre-trained model, you can train one using your data and save it as 'keras_model.h5'.
Open a terminal or command prompt, navigate to the directory containing the code and run: streamlit run app.py.
A browser window will open, and you can interact with the web application to predict stock trends.

Features
------------------

Enter the stock ticker of your choice to visualize its closing prices over time.
View the descriptive statistics of the stock's closing prices from 2010 to 2023.
Observe the closing price versus time chart, both standalone and with 100-day and 200-day moving averages.
See the predictions of the stock's closing prices against the actual prices using the pre-trained Keras model.

Code Structure
------------------
app.py: This file contains the Streamlit application code. It imports the necessary libraries, fetches stock data using the Yahoo Finance API, preprocesses the data, and makes predictions using the pre-trained Keras model. The application is organized into functions for data preprocessing, loading and predicting the stock data, and for displaying the visualizations.
keras_model.h5: This file contains the pre-trained Keras model. If you don't have a pre-trained model, you can train one using your data and save it as 'keras_model.h5'.
requirements.txt: This file lists all the required dependencies along with their versions.

Contributing
------------------
Feel free to contribute to this project by creating pull requests for bug fixes, enhancements, or additional features. You can also open issues for any bugs or suggestions you come across.

Disclaimer
------------------
This application is for educational and informational purposes only. The stock predictions made by the model may not be accurate and should not be considered as financial advice. Always consult a professional financial advisor before making any investment decisions.

Acknowledgments
------------------
This project was inspired by the desire to learn and explore the concepts of data analysis, machine learning, and web application development using Streamlit. Many thanks to the open-source community and all the libraries that made this project possible.
