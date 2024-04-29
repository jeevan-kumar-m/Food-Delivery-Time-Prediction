## Food-Delivery-Time-Prediction


**Problem Statement**: The goal is to predict the delivery time based on the distance covered by the delivery partner to deliver the order.

## Data Exploration:

The dataset contains information about delivery orders, including details about delivery partners, restaurants, delivery locations, and time taken for delivery.
Initial data exploration includes understanding the structure of the dataset, checking for missing values, and visualizing the relationships between variables.
Feature Engineering:

Calculating distance between the restaurant and delivery locations using latitude and longitude coordinates.
Adding the calculated distance as a new feature ('distance') to the dataset.

## Modeling:

Splitting the dataset into training and testing sets.
Utilizing a Long Short-Term Memory (LSTM) neural network model for prediction.
The model architecture includes two LSTM layers followed by dense layers.
Compiling the model using Adam optimizer and mean squared error loss function.
Training the model on the training data with a batch size of 1 and 9 epochs.
Prediction:

Taking input values such as delivery partner's age, ratings of previous deliveries, and total distance.
Using the trained model to predict the delivery time in minutes based on the provided input features.


## Summary:

The solution provides a predictive model that can estimate the delivery time for food orders based on the distance covered by the delivery partner.
By utilizing historical data and machine learning techniques, the model offers insights into the relationship between delivery time and various factors such as distance, delivery partner's age, and ratings.

