# Data-Science-and-Big-Data-Analytics
This repository contains projects and code related to Data Science and Big Data Analytics. These projects aim to explore various aspects of data analysis, machine learning, and big data processing. The code and examples provided here serve as a resource for understanding and implementing data science techniques and working with large datasets.


Installation
To run the code and projects in this repository, you need to have the following dependencies and libraries installed:

Python 3.x
Jupyter Notebook
NumPy
Pandas
Scikit-learn
TensorFlow
Apache Spark (for big data projects)

Project Description

Data Wrangling I
This project focuses on performing data wrangling operations using Python on an open source dataset. The steps involved are as follows:

Import all the required Python Libraries.
Locate an open source dataset from the web, such as https://www.kaggle.com. Provide a clear description of the data and its source (URL of the website).
Load the dataset into a pandas dataframe.
Perform data preprocessing by checking for missing values using the isnull() function and obtaining initial statistics using the describe() function. Provide variable descriptions, types of variables, and check the dimensions of the dataframe.
Summarize the types of variables by checking their data types (character, numeric, integer, factor, logical). If variables are not in the correct data type, apply proper type conversions.
Turn categorical variables into quantitative variables in Python.
Data Wrangling II
In this project, we create an "Academic performance" dataset of students and perform the following operations using Python:

Scan all variables for missing values and inconsistencies. If there are missing values and/or inconsistencies, use suitable techniques to deal with them.
Scan all numeric variables for outliers. If there are outliers, use suitable techniques to deal with them.
Apply data transformations on at least one variable. The purpose of this transformation should be to change the scale for better understanding of the variable, convert a non-linear relation into a linear one, or decrease skewness and convert the distribution into a normal distribution. Properly reason and document the approach.
Descriptive Statistics - Measures of Central Tendency and Variability
In this project, we perform descriptive statistics on a dataset with numeric variables grouped by a qualitative (categorical) variable. The steps involved are as follows:

Provide summary statistics (mean, median, minimum, maximum, standard deviation) for a dataset (e.g., age, income) with numeric variables grouped by a categorical variable (e.g., age groups). Create a list that contains a numeric value for each response to the categorical variable.
Write a Python program to display basic statistical details like percentile, mean, standard deviation, etc. of the species 'Iris-setosa', 'Iris-versicolor', and 'Iris-virginica' in the iris.csv dataset.
Data Analytics I
This project involves creating a Linear Regression Model using Python/R to predict home prices using the Boston Housing Dataset from Kaggle. The dataset contains information about various houses in Boston with 506 samples and 14 feature variables.

Data Analytics II
In this project, we implement logistic regression using Python/R to perform classification on the Social_Network_Ads.csv dataset. We compute the confusion matrix to find true positives (TP), false positives (FP), true negatives (TN), false negatives (FN), accuracy, error rate, precision, and recall.

Data Analytics III
For this project, we implement Simple Naïve Bayes classification algorithm using Python/R on the iris.csv dataset. We compute the confusion matrix to find true positives (TP), false positives (FP), true negatives (TN), false negatives (FN), accuracy, error rate, precision, and recall.

Text Analytics
This project involves extracting a sample document and applying document preprocessing methods such as tokenization, POS tagging, stop words removal, stemming, and lemmatization. We also create a representation of the document by calculating Term Frequency and Inverse Document Frequency.

Data Visualization I
In this project, we use the inbuilt 'titanic' dataset, which contains information about the passengers who boarded the Titanic ship. We use the Seaborn library to find patterns in the data and plot a histogram to check the distribution of ticket prices.

Data Visualization II
Using the 'titanic' dataset, we plot a box plot for the distribution of age with respect to each gender, along with information about whether they survived or not. We observe and analyze the statistics from the visualization.

Data Visualization III
For this project, we download the Iris flower dataset (or any other dataset) into a DataFrame. We scan the dataset and provide the following inferences:

List down the features and their types (e.g., numeric, nominal) available in the dataset.
Create a histogram for each feature in the dataset to illustrate the feature distributions.
Create a box plot for each feature in the dataset.
Compare distributions and identify outliers.
