# CMPT353 PROJECT: Heart-Failure-Prediction
In this project, we predict a user's heart failure probability based on a certain set of input features like Age, RestingBP, Cholesterol, Heart Rate, etc.

#### _A report with all the analysis and details of the used techniques is saved as file CMPT 353 Report.pdf_

## **Table of contents**
* [General info](#general-info)
* [Technologies](#technologies)
* [Libraries Used](#libraries-used)
* [Features](#features)
* [Order Of Execution](#order-of-execution)
* [Status](#status)
* [Based On](#based-on)
* [Created By](#created-by)

## General info
The idea behind this project is to predict a person's HeartDisease condition based on a certain set of input features using machine learning algorithms. Data was borrowed from [here](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction). Statistical tests were used to analyze the data. Feature engineering was used for training Machine Learning models.

## Technologies
This code was written on `Python v3.8.10`. A `requuirements.txt` file has been provided to setup and re-run the project again with all of it's dependencies.

## Libraries Used
* numpy
* pandas
* matplotlib 
* statsmodels
* scipy 
* sklearn
* joblib

## Features
* Data analysis and preprocessing
* Statistics
* Machine Learning

## Order Of Execution

1) Create a new virtual environment
    * Firstly, setup a virtual environment. There are a number of methods to do so, but we will be using `virtualenv`

    ```
    virtualenv venv
    ```
    * Activate the newly created virtual environment.
    ```
    source venv/bin/activate
    ```
    * Install the project dependencies
    ```
    pip install -r requirements.txt
    ```
2) Run `01. Getting Data.ipynb` 
    * Results produced: Extract `heart.csv` data file from the included archive to be used further.
3) Run `02. Analsis and Statistics.ipynb`
    * Perform EDA
    * Separate input features into numerical and categorical features
    * Remove outliers
    * Perform inferential and statistical tests.
4) Run `03. Machine Learning.ipynb`
    * Encode categorical values into numerical values
    * Train/Test Split
    * Feature Scaling
    * Run vaious machine learning models and log and plot results.

5) Run `04. Machine Learning - Tuned Models.ipynb`
    * Run the previous machine learning models but with tuned parameters using GridSearchCV

## Status
Project is:  _Finished_

## Based on
Project based on Computational Data Science

## Created By
Created by Eshaan Pal Singh and Supreet Singh Dhillon