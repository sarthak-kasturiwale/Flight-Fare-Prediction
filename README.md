# Flight-Fare-Prediction
The project is based on 'Prediction on flight price', a hackathon hosted on machinehack.com.

# Problem Statement
- Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story.
- We might have often heard travelers saying that flight ticket prices are so unpredictable. As data scientists, we are gonna prove that given the right data anything can be predicted.
- Here we will be provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities. We have to predict the prices

# Dataset Description
- The Dataset can be downloaded from https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh
- We will be using two datasets — Train data and Test data.
- Training data is combination of both categorical and numerical also we can see some special character also being used because of which we have to do data Transformation on it before applying it to our model.
- The test data is similar to the training data set, minus the 'Price' column (To be predicted using the model).
  1. Size of training set: 10683 records
  2. Size of test set: 2671 records

# Approach for Problem Solving
1. Understanding the Problem
2. Downloading the Dataset
3. Importing necessary Dependencies
4. Exploratory Data Analysis
5. Feature Engineering for Training Data
6. Applying the Same Procedure for Test Data
7. Building the Model
8. Evaluation of the Model
9. End Results
10. Final Sample Submission

# End Results
- As the Train R2 is Highest for Random Forest Regressor i.e about 0.8317659189007600, we will select it for Predicting the Values for Test Data.
