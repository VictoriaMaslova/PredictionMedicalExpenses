# Prediction Medical Expenses

## How to run the code

### Option1. Running using free online resource

You can find highly-detailed explanation, try the code directly on [Kaggle Notebook](https://www.kaggle.com/victoriamiller19/linear-regression-with-tool-scikit-learn). Save a copy in your drive and enjoy It!

### Option 2: Running on your computer locally
* Install VS Code.
* Setup a Python environment. On mac OS, it already has Python 2 but I recommend not using that. Instead, I recommend installing Python 3 via Homebrew.
* Install the Jupyter package.
* Select the Python environment (with the Jupyter package)
* Open and edit .ipynb files.

## Problem Description
This tutorial takes a practical and coding-focused approach. We'll define the terms machine learning and linear regression in the context of a problem, and later generalize their definitions. We'll work through a typical machine learning problem step-by-step:

```QUESTION: ACME Insurance Inc. offers affordable health insurance to thousands of customer all over the United States.
As the lead data scientist at ACME,
you're tasked with creating an automated system to estimate the annual medical expenditure for new customers, 
using information such as their age, sex, BMI, children, smoking habits and region of residence.

Estimates from your system will be used to determine
the annual insurance premium (amount paid every month) offered to the customer.
Due to regulatory requirements, you must be able to explain why your system outputs a certain prediction.
```


You're given a [CSV file](https://github.com/VictoriaMaslova/PredictionMedicalExpenses/blob/main/insurancedata.csv) containing verified historical data, consisting of the aforementioned information and the actual medical charges incurred by over 1300 customers.



## Data Summary
![](https://github.com/VictoriaMaslova/PredictionMedicalExpenses/blob/main/dataset.png)


### Here are some statistics for the numerical columns:
![](https://github.com/VictoriaMaslova/PredictionMedicalExpenses/blob/main/somestats.png)




## The following topics are covered in this tutorial:

* A typical problem statement for machine learning
* Downloading and exploring a dataset for machine learning
* Linear regression with one variable using Scikit-learn
* Applying linear regression to other datasets


## How to Approach a Machine Learning Problem

**Here's a strategy you can apply to approach any machine learning problem:**

* Explore the data and find correlations between inputs and targets
* Pick the right model, loss functions and optimizer for the problem at hand
* Scale numeric variables and one-hot encode categorical data
* Set aside a test set (using a fraction of the training set)
* Train the model
* Make predictions on the test set and compute the loss
* We'll apply this process to several problems in future tutorials.
