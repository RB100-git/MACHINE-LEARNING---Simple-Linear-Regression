# Simple Linear Regression
# Modelling Linear relationship between Weight and Height dataset
The contents of this project are divided into following topics which are listed as follows:-

# Table of Contents
(1) Project overview

(2) Python libraries

(3) Independent and dependent variable

(4) Linear Regression

(5) Simple Linear Regression

(6) About the dataset

Exploratory data analysis

Mechanics of Simple Linear Regression

Model slope and intercept term

Making predictions

Regression metrics for model performance i. RMSE ii. R2 Score

Interpretation and conclusion

Residual analysis

Checking for Overfitting or Underfitting the data

Simple Linear Regression - Model Assumptions


# (1) Project overview
In this project, I build a Simple Linear Regression model to study the linear relationship between Weight and Height of a dataset.

# (2) Python libraries
I have Anaconda Python distribution installed on my system. It comes with most of the standard Python libraries I need for this project. The basic Python libraries used in this project are:-

• Numpy – It provides a fast numerical array structure and operating functions.

• pandas – It provides tools for data storage, manipulation and analysis tasks.

• Scikit-Learn – Scikit-learn is a key library of Python, focused on machine learning tools including mathematical, statistical and general purpose algorithms that form the basis for many machine learning technologies. 

• Matplotlib – It is the basic plotting library in Python. It provides tools for making plots.

# (3) Independent and Dependent Variables
In this project, I refer Height as Independent variable and Weight as Dependent variable as Target variable.

Independent variable
Independent variable is also called Input variable and is denoted by x. The independent variable is the cause. Its value is independent of other variables. We can denote it as: - Independent or Input variable (x) = Feature variable

Dependent variable
Dependent variable is also called Output variable and is denoted by y. The dependent variable is the effect. Its value depends on changes in the independent variable. It can be denote it as follows: -

Dependent or Output variable (y) = Target variable

# (4) Linear Regression
Linear Regression is a statistical technique which is used to find the linear relationship between dependent and one or more independent variables. This technique is applicable for Supervised Learning Regression problems where we try to predict a continuous variable. Linear Regression can be further classified into two types – Simple and Multiple Linear Regression. In this project, I employ Simple Linear Regression technique where I have one independent and one dependent variable. It is the simplest form of Linear Regression where we fit a straight line to the data.

# (5) Simple Linear Regression
Simple Linear Regression (or SLR) is the simplest model in machine learning. It models the linear relationship between the independent and dependent variables.

In this project, there is one independent or input variable which represents the Height data and is denoted by x. Similarly, there is one dependent or output variable which represents the Weight data and is denoted by y. We want to build a linear relationship between these variables. This linear relationship can be modelled by mathematical equation of the form:-

			Y = β0   + β1*X    -------------   (1)
In this equation, X and Y are called independent and dependent variables respectively, β1 is the coefficient for independent variable and β0 is the constant term. β0 and β1 are called parameters of the model.

For simplicity, we can compare the above equation with the basic line equation of the form:-

    			y = ax + b       ----------------- (2)
We can see that

slope of the line is given by, a = β1, and

intercept of the line by b = β0.

In this Simple Linear Regression model, we want to fit a line which estimates the linear relationship between x and y.

# (6) About the dataset
The data set has been imported from the kaggle website with the following url-

https://www.kaggle.com/datasets/mustafaali96/weight-height

This dataset contains Gender, Height and Weight columns. The weight-height data has 10000 rows and 3 columns.
