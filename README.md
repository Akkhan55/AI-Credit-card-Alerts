# Credit Card Alert System for personal use

The objective factor, whether the utilization rate exceeds 30% or not, is determined by the model being trained on a dataset containing information on credit card usage. The machine learning algorithm used by the code, random forest regression, trains the model using the data input. The user is next required to enter the approved credit card limit and the current amount, after which the code calculates the user's credit card use rate. The model is used to estimate whether or not the calculated utilization rate will surpass 30%.

# About
This program begins by importing the pandas and scikit-learn libraries, both of which are strong Python libraries for working with data and creating machine learning models. The credit card use data is then loaded from a CSV file named "credit card usage.csv" using the pandas read csv function.
The data is then divided into features (X) and targets (y), with the features being the different qualities of credit card usage (such as costs, income, and so on) and the targets being whether the credit card limit was exceeded. It trains a random forest model with these characteristics and target, which may be used to forecast if the credit card limit will be surpassed based on the credit card use attributes.
