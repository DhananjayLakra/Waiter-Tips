# Waiter-Tips
Used Linear Regression model to predict the amount of a tip a waiter will get. The model was trained on multiple features like total_bill, sex, smoker, day, time and size; all of which are described below. 

# About the Dataset:
the dataset can also be found on [kaggle](https://www.kaggle.com/datasets/jsphyg/tipping)

the fields are explained below:

total_bill: Total bill in dollars including taxes

tip: Tip given to waiters in dollars

sex: gender of the person paying the bill

smoker: whether the person smoked or not

day: day of the week

time: lunch or dinner

size: number of people in a table 

The non-numeric fields, such as "day" are encoded into suitable numeric values before passing them into the model. Once the model is trained, it is used to make predictions and is also tested for overfitting. A test MSE score of 0.92 was achieved 
