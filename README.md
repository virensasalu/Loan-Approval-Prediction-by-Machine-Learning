# Loan-Approval-Prediction-by-Machine-Learning
Predicting if a customer might default or not based on some attributes.

# Final Project - German Bank Loan
**Objectives:**


1. Introduction

* Data Description
* Some of the Questions I have answered throughout the program

2. Methods and Materials

* Exploratory Data Analysis (EDA)
* Data Understanding, Cleaning and Pre-Paring/Pre-Processing
* Data Visualization: ‘Datavis’
* My Observations
* Data Pre-Processing
* Models Training: ‘ProcessedBankData’
* Model fitting and Evaluations
* Model Comparison and Final Selection

3. Result

* Logistic Regression
* K-Nearest Neighbours
* Quadratic Discriminant Analysis
* Random Forest
* Gradient Boosting
* AdaBoost
* Linear Discriminant Analysis

4. Discussion

* General Thoughts
* Least performing models and its observation
* Best Performing model and its observation
* Limitations 
* Citations

5. Conclusion





Structure of my Code file Named: Final Project- The German Bank
Submitted as IPYNB (notebook) and an HTML page
Submitted on 29th November, 2023
My apologies, my code file is a little different from the structure of my final report. But rest assured all the results are from the code file 



1. General Introduction to the problem statement

* Objectives
* Context
* Data Description
* Some Questions I have answered throughout the program
* Importing all the libraries that might be need pre-emotively
* Reading the data set to being with understanding it and then processing it

2. Pre-Processing

* Checking the data in depth to make sure there no anomalies (some insights shared)
* Cleaning up the dataset, getting rid of all the anomalies
* Making different copies of the dataset. One for data visualization (Datavis) and one for models (ProcessedBankData)
* Mapping the dataset to fit the models (Insights)

3. Exploratory Data Analysis for Bank data

* Making more sense of the data by drafting graphs and learning the relationship between each attributes
* PairPlot (numerical features only)
* plotly.express
* Heat map – of selected features only (Numerical and some categorical)
* Correlation matrix
* Box plot, density and histogram with hue= default 
* Count plot of all the features without default

4. Exploring Machine Learning Models

* Splitting the data to 80 - 20 with stratification
* Initialize StandardScaler and fit-transform on the training and test data
* Model 1 random forest
* Understanding the feature importance
* Checking how well the model fits
* Models 2,3,4,5,6,7
* Last leg 
* Plotting all confusion matrix
 
5. Comparing The Model Performance

* Adapted Precision Recall curve, Area Under Curve, Receiver Operating Characteristic curve
* Created a dummy dataset to fit to my model.(Deployment proof)






The objective of the final project will be to build a fully reproducible project that uses ML to address a question of your choice (e.g. in academic or industry).The dataset required for this project is provided along with this document (see details below). This is an individual project. Since this course is an advanced undergraduate/graduate student level course, it is expected that the final report should be publishable and fully reproducible.
**Context:**

This data set contains historical data of the customers who have taken loans from a German bank and the bank is facing issues with loan defaulters. The bank intends to build a machine learning model to predict whether the customer will default or not based on historical data

**Data Description:**

The bank has historical information on relevant features for each customer such as employment duration, existing loans count, saving balance, percentage of income, age, default status. 

The data set has 17 columns and 1000 rows. Columns are described below and each row is a customer. 

- checking_balance - Amount of money available in account of customers
- months_loan_duration - Duration since loan taken
- credit_history - credit history of each customers
- purpose - Purpose why loan has been taken
- amount - Amount of loan taken
- savings_balance - Balance in account
- employment_duration - Duration of employment
- percent_of_income - Percentage of monthly income
- years_at_residence - Duration of current residence
- age - Age of customer
- other_credit - Any other credits taken
- housing- Type of housing, rent or own
- existing_loans_count - Existing count of loans
- job - Job type
- dependents - Any dependents on customer
- phone - Having phone or not
- default - Default status (Target column)


**Some Questions I have answered throughout the program**

- What are some of the best ML models right for this dataset?
- How will I determine the right model amongst all the models?
- How does some features effect the 'default'?
- what are the feature importance, using Feature importance?
- Perform complete EDA.
- How will you address the dataset, to fit the model. will you use one-hot-encoding? or Map each attributes?
- How can you determine if the models are under fitting/overfitting?
- How are you accessing the accuracy and laying all the models heat map?
- What steps will you take to compare the models
- Create a dummy dataset and predict the defaults(Deployment proof)?
