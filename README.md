# usd-inr-forex-prediction
USD-INR Forex Prediction using Machine Learning

**Project Overview**
This project predicts USD to INR exchange rates using historical forex data and a machine learning model.

**Dataset**
The dataset contains daily USD/INR exchange rates from 2017 to 2022. It includes Date, Open, High, Low, and Close values.

**Technologies Used**
Python
Pandas
Matplotlib
Scikit-learn

**Methodology**
The dataset was loaded and cleaned by removing missing values.
The Date column was converted into datetime format.
A new column called Days was created by converting dates into numerical values.
The data was split into training and testing sets.
A Linear Regression model was used to train the data.
Predictions were made using the trained model.

**Results**
The model was evaluated using Mean Squared Error.
MSE value is approximately 3.6.
The model predicted future exchange rate around 78 INR for a given day.

**Conclusion**
The model provides a basic understanding of exchange rate prediction.
Accuracy can be improved using advanced machine learning models and more data.
