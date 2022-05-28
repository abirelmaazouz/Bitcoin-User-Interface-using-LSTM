# Bitcoin-User-Interface-using-LSTM
Data Analytics and Advanced Programming Semester Project - HEC Lausanne MScF 2022

{ Bitcoin Future Price Prediction

The project relies on two different parts:

Machine Learning model : A Deep Recurrent Neural Network (long short term memory algorithm(LSTM)) to make bitcoin price predicitions for the 7 next days using TensorFlow.

A Graphical user interface (GUI): To present information to potential bitcoin investors, among them the future predictions.

********************************************** Machine Learning model*******************************************

Deep Recurrent Neural Network (LSTM) is a machine learning model often used in finance to make stock prediction prices. Install:

This project part requires Python and the following Python libraries installed:

- Pandas
- matplotlib
- numpy
- seaborn
- datetime
- plotly.express
- time
- tenseorflow
- sklearn
- joblib

The source code is divided into multiple sections following the machine learning design pattern :

Data Exploration
Data cleaning,
Data Splitting and normalization
Determining best and optimal performing model architecture
Keras model Application with different layers and model fitting
Forecast for future prices
We recommend you perform this on software (as pycharm) in order to have the GUI application. If you are only interested in machine learning, you can compile this on a notebook and can view the precompiled version of the notebook or you can rerun the entire notebook. Running the algorithm will automatically actualize the data set and download future predictions on a CSV file.

**BTCRYPTO PLATFORM This project part requires Python and the following Python libraries installed:

Libraries create the interface:

- Tkinter
- from tkinter : messagebox
- customtkinter

Libraries to diplay plots and pie charts:

- matplotlib
- From matplotlip : FigureCanvasTkAgg, Figure, animation, style

Library for the data :

- yfiance

Other useful libraries :

- PIL
- datetime
- requests
- os
- pandas
- numpy

BTCRYPTO Plateform is a graphical user interface constructed with Tkinter python. The design of the interface has been updated with the custom Tkinter library. The platform enables the potential bitcoin investor to have enough information about the bitcoin market and rather he should invest or not. A Twitter API is used to display the last bitcoin information tweets from the Twitter account @BTCTN.

Frames of the interface :

- Start page (main page)
- User cryptocurrency portfolio visualisation
- Current Bitcoin market
- Bitcoin useful informations
- Twitter page, useful recent tweets about bitcoin
- Prediction prices for the 7 next days ( dowloawded from the machine learning part with a CSV file)
- - Prediction prices for the 6 next months ( dowloawded from the machine learning part with a CSV file)
**RUN

To run everything and have good results, you should first run the machine learning algorithm to download future bitcoin prices and then the BTCRYPTO platform algorithm to be able to display predictions on the graphical user interface.

You will also need to have software installed to run and execute.

******************************************************* DATA *****************************************************

Machine Learning :

Bitcoin data prices, in the machine learning algorithm, are from crypto Data download .com (https://www.cryptodatadownload.com/cdd/Binance_BTCUSDT_d.csv). It is a daily updated data set that take Bitcoin’s information starting from January 1st, 2020. The prices are in dollars.

GUI :

BitCoin Data price, in the platform algorithm, are from https://finance.yahoo.com/quote/BTC-USD/history?p=BTC-USD. The price is actualized every five minutes. The prices are in dollars.

Target Variable Close Price: Close price of Bitcoin. }
