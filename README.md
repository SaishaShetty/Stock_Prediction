# Stock_Prediction

This project was built as a part of the Sparks Foundation Internship, in which as a Data Science and Business Analytics Intern, I was asked to predict the stock prices and perform Sentimental analysis on the News headlines. 

## TASK
Stock Market Prediction Using Numerical and Textual Analysis

## OBJECTIVE
Create a hybrid model for stock price/performance prediction using numerical analysis of historical stock prices, and sentimental analysis of news headlines.

We will be using Recurrent Neural Networks with LSTM Sequential Model. 

# The Project was split into:
1. Importing the data from yahoo finance.We used Microsoft stock data for the model.
2. Creating the data frame for close price. We will only use Close price for this model.
3. Scaling the data. We will be using MinMaxScaler. MinMaxScaler is used when we need to rescale the dataset such that the features values are in the range [0,1]
4. Reshaping the training data which can be used in the LSTM Model.
5. Compile the Model.
6. Preparing the test data, feature scaling and reshaping.
7. Predicting the output from from the test data.
8. Scaling the data back to the original format.
9. Comparing our model's prediction with the actual closing price.
10. Applying Sentimental Analysis on News Headline. 
  
