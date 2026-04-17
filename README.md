<img width="1920" height="973" alt="output ss" src="https://github.com/user-attachments/assets/3406d665-634a-4da3-abae-a57d627f0015" />
# usd-inr-forex-prediction
USD-INR Forex Prediction using Machine Learning

**Project Overview**
This project focuses on predicting the USD to INR exchange rate using historical foreign exchange data. The goal is to analyze past trends and build a machine learning model that can estimate future currency values. This helps in understanding how exchange rates change over time and demonstrates a basic forecasting approach.

**Problem Statement**
Currency exchange rates fluctuate daily due to various economic factors. Predicting these changes is important for businesses, investors, and financial analysis. This project aims to build a simple predictive model using historical data.

**Dataset**
The dataset contains daily USD/INR exchange rate data from 2017 to 2022. It includes the following columns:
Date - The trading date
Open - Opening exchange rate
High - Highest rate of the day
Low - Lowest rate of the day
Close - Closing exchange rate

**Data Preprocessing**
The dataset was cleaned and prepared before applying machine learning techniques.
Missing values were removed to avoid errors during training.
The Date column was converted into datetime format for proper time handling.
The dataset was sorted in chronological order.
A new feature called Days was created by converting dates into numerical values, since machine learning models require numeric input.

**Exploratory Data Analysis**
A line graph was plotted using Date and Close values to visualize exchange rate trends over time.
This helped in identifying patterns, fluctuations, and general movement of the currency.

**Model Used**
Linear Regression was used as the machine learning model.
It is a simple and widely used algorithm for predicting continuous values.
The model learns the relationship between time (Days) and exchange rate (Close value).

**Model Training**
The dataset was divided into training and testing sets using an 80:20 ratio.
The training data was used to train the model.
The testing data was used to evaluate model performance.

**Evaluation Metric**
Mean Squared Error (MSE) was used to measure the accuracy of the model.
The obtained MSE value is approximately 3.6, indicating a reasonable prediction error for a basic model.

**Prediction**
The trained model was used to predict future exchange rates.
For example, the model predicted a value of around 78 INR for a future day input.

**Results**
The model was able to capture the general trend of the exchange rate.
Predictions were close to actual values but not perfectly accurate due to model simplicity.

**Conclusion**
This project demonstrates a basic approach to time-based prediction using Linear Regression.
While the model performs reasonably well, accuracy can be improved by using advanced techniques such as time series models or deep learning methods.
More features and updated data can also enhance performance.

**Future Improvements**
Use advanced models like ARIMA, LSTM, or Random Forest.
Include additional economic indicators for better prediction.
Improve accuracy by tuning model parameters.
Use real-time data for better forecasting.

**Technologies Used**
Python
Pandas
Matplotlib
Scikit-learn
Google Colab
