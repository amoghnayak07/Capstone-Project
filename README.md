# Titanic Survival Prediction
Would you have survived the crash if you were ever on board the Titanic?
Would you have better chances of survival if you were a 20 year old female traveling first class with no relatives on board?

Let's try to answer these questions with the help of python tools and a few machine learning algorithms. 

## Install
This project requires python 3.6 or any other higher versions of python along with the following libraries installed:

* Numpy
* Pandas
* matplotlib
* scikit-learn

You also need a software to run this python notebook, "Jupyter Notebook". It is hghly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

# Description of the repository

This repository contains 1 notebook:

* "Titanic Capstone Project.ipynb" : This notebook contains linear regression and Neural Networks implementation of the dataset.

# Attribute information

* PassengerrId - Unique identification number given to each passenger.

* Pclass - Type of class each passenger is traveling in.

* Sex - Gender of each passenger.

* Age - Age of each passenger.

* SibSp - Number of siblings traveling with each passenger.

* Parch - Number of parents or children traveling with each passenger.

* Ticket - Unique ticket information given to each passenger.

* Fare - Fare, in dollars, paid by each passenger for their seat on the Titanic

* Cabin - Cabin occupied by each passenger.

* Embarked - Place of boarding the Titanic.

# Output Variable (desired target)

* Survived - categorical  - Tells if the passenger did survive or did not survive.

# Models trained on:

Training model | Accuracy
-------------- | --------
Linear Regression | 77.65%
Neural Networks | 82.02%

# Loss curve:

![Loss curve](C:\Users\BATCOMP\Desktop\Loss_curve.png)
