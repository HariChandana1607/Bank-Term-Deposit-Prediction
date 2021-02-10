# Bank-Term-Deposit-Prediction

## Objective: 

Term deposits are major revenue sources for banks. The project is related to direct marketing
campaigns in banks, where we will predict the probability that a customer contacted by the phone banking
team will subscribe for a term deposit. The project will also indicate the key variables that impact
conversion.

## About the dataset

The source data consists of the following are the variables provided for 41188 customers:
age: Age of customer
job: type of job
marital: marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced
or widowed)
education: Customer education level
default: has credit in default?
housing: has housing loan?
loan: has personal loan?
Related with the last contact of the current campaign:
contact: contact communication type
month: last contact month of year
day_of_week: last contact day of the week
Other attributes:
campaign: number of contacts performed during this campaign and for this client
pdays: number of days that passed by after the client was last contacted from a previous campaign (999
means client was not previously contacted)
previous: number of contacts performed before this campaign and for this client
poutcome: outcome of the previous marketing campaign
Social and economic context attributes:
emp.var.rate: employment variation rate - quarterly indicator
cons.price.idx: consumer price index - monthly indicator
cons.conf.idx: consumer confidence index - monthly indicator
euribor3m: euribor 3 month rate - daily indicator
nr.employed: number of employees - quarterly indicator
Output variable (desired target):
y: has the client subscribed a term deposit? (binary: 'yes','no')

## Project Instructions
1. Perform the required data pre-processing to treat for missing values and outliers
2. Perform exploratory data analysis to visualise the spread of each of the X variables and the
relationship between the various X variables and the Y variable
3. Divide the given data into train and test sets
4. Predict customer propensity to subscribe to a term deposit by building classification models
5. Interpret how each of the X variables influence the conversion propensity
6. Evaluate the model performance measures and choose the most optimum model
7. Enlist your key findings based on the most optimum model and the respective feature importance
