# Predict The Flight Ticket Price

Flight ticket prices can be highly unpredictable, fluctuating from one day to the next. This project aims to tackle the challenge of predicting flight ticket prices using data science techniques. With the right data and machine learning algorithms, we can demonstrate that flight ticket prices are not as unpredictable as they seem.

## Overview

In this project, we are provided with prices of flight tickets for various airlines between the months of March and June of 2019, along with information about the airlines, journey dates, sources, destinations, routes, departure and arrival times, durations, and additional details.

- **Training Set Size**: 10,683 records
- **Test Set Size**: 2,671 records

## Features

- **Airline**: The name of the airline.
- **Date_of_Journey**: The date of the journey.
- **Source**: The source from which the service begins.
- **Destination**: The destination where the service ends.
- **Route**: The route taken by the flight to reach the destination.
- **Dep_Time**: The time when the journey starts from the source.
- **Arrival_Time**: Time of arrival at the destination.
- **Duration**: Total duration of the flight.
- **Total_Stops**: Total stops between the source and destination.
- **Additional_Info**: Additional information about the flight.
- **Price**: The price of the ticket.

## Data Preprocessing and Feature Engineering

- **Feature Engineering**: Extracting features like journey date, month, and year from the date of the journey. Splitting and encoding categorical variables.
- **Handling Missing Values**: Filling missing values and converting data types.
- **Feature Selection**: Using Lasso regression for feature selection.
- **Training**: Utilizing Random Forest Regression for model training.
- **Testing**: Evaluating the model on the test dataset.

## Usage

1. **Data Preparation**: Load and preprocess the training and test datasets.
2. **Feature Engineering**: Extract relevant features and handle missing values.
3. **Feature Selection**: Select important features using Lasso regression.
4. **Model Training**: Train the Random Forest Regression model using the training data.
5. **Model Evaluation**: Evaluate the model's performance using the test dataset.
6. **Prediction**: Predict flight ticket prices on new data.

## Dependencies

- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

## Files

- `Data_Train.xlsx`: Training dataset
- `Test_set.xlsx`: Test dataset
- `Predict_The_Flight_Ticket_Price.ipynb`: Jupyter Notebook containing the Python code for data preprocessing, feature engineering, model training, and evaluation.

