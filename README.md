# Python_code
Welcome to my Python code repository. As of now, the notebooks that you see here are taken from the projects that I worked on as part of my Machine Learning with Python course on Coursera. The datasets used in the notebooks are taken from IBM's cloud storage. I've explained the topics of these projects in brief below.

## Logistic Regression - Churn Dataset
The dataset is based on a fictional telecom company that provided home phone and internet services to 7043 customers in California during one financial quarter. The main dependent variable in the model is **Churn**, which is a categorical variable which equals 1 when the customer left the company in the quarter, and 0 when the customer remained with the company. Key regressors include:
* **tenure**: the total amount of months that the customer has been with the company by the end of the quarter,
* **age**: age of the customer in years,
* **address, income and ed (education), employ**: fictional values, address as a code for an area, income in $'000 p.a., total years of education, and total number of years employed and,
* **equip**: a categorical variable which equals 1 when the customer has bought an equipment from the company and 0 otherwise. 

A standard logistic regression model was used and the model was evaluated by splitting the entire dataset into train and test sets with the test set containing 20% of the observations chosen at random. Model evaluation scores used were the Jaccard index and a confusion matrix.

## Machine Learning with Python - Final Project
My largest project on Python so far, this was the final project that I submitted as part of my course. Two datasets were used:
* **Loan_train (training set)**: includes details of 346 customers whose loan are already paid off or defaulted and,
* **Loan_test (test set)**: similar dataset which includes details of 53 customers whose loan are already paid off or defaulted.

I used 4 classification techniques, namely:
1. K-Nearest Neighbors
2. Decision Trees
3. Support Vector Machines
4. Logistic Regression

to fit the four models on the training set, use the fitted models to predict the test set, find out the performance of the models using a few scores and report on the accuracy of these models. I used three scores for all the models:
1. Jaccard Score,
2. F1 Score and,
3. Log-Loss (only for logistic regression).

During the fitting part of the analysis, I splt the training set into smaller train and test sets for locally evaluating model performance, and in the case of KNN, to find out the best value for K.

## Multiple Linear Regression
The dataset used here is based on the information collected from 1067 cars on their fuel consumtion on city roads and highways as well as their CO<sub>2</sub> emissions. The main dependent variable here is **co2emissions**, which is a continuos variable measuring the CO<sub>2</sub> of a car of a particular make, model and vehicle class. Key rregressors include:
* **enginesize**: size of the car's engine in cubic litres,
* **cylinders**: the number of cylinders in a car's engine,
* **fuelconsmuption_city, fuelconsmuption_hwy and fuelconsmuption_comb**: the fuel consumption of a car per kilometre travelled in city roads, highways and both combined, respectively.

A standard linear regression model was used and the model was evaluated by splitting the entire dataset into train and test sets with the test set containing 20% of the observations chosen at random. Model evaluation scores used were the Mean Absolute Error, Mean Squared Error and R<sup>2</sup>.



