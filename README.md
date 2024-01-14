# Click_Rate_Prediction
This is part of the code for predicting the click rate. The orignal dataset includes information from users, merchants and requests. The goal is to use the past requests information (searching query, searching time), the demographic information of users and merchants to predict the click rate.

## Feature Engineering For Merchants
* Manual Features:
    * The Average Price and Score For the past 30 days
    * The difference between the average price and the average price of merchants in the same category, the category includes kind and location.
    * The average exposure rate for the past 30 days and 7 days

## Data Manipulation and DIEN Application
The DIEN (Deep Interest Evolution Network) model is an innovative neural network architecture designed for personalized recommendation systems, integrating both short-term and long-term user interests to enhance the accuracy and effectiveness of recommendations in dynamic scenarios. 
* Here, I engage in data manipulation and reformatting, ensuring its seamless integration into the DIEN library for further processing and analysis.

