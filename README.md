# Customer-Conversion-prediction
Customer Conversion Prediction project is to build a machine learning model that can predict whether a client will subscribe to the insurance based on their demographic and marketing data.

## Table of Contents
- [Problem Statement](#problem-statement)
- [Features](#features)
- [Output Variable](#output-variable)
- [Minimum Requirements](#minimum-requirements)
- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)
- [Usage](#usage)
- [Author](#author)

## Problem Statement
We are working for a new-age insurance company that employs multiple outreach plans to sell term insurance to customers. Telephonic marketing campaigns remain one of the most effective ways to reach out to people, but they also incur a lot of cost. Therefore, it is important to identify customers who are most likely to convert beforehand so that they can be specifically targeted via calls. The goal of this project is to build a machine learning model that predicts whether a client will subscribe to the insurance.

## Features
- age (numeric)
- job: type of job
- marital: marital status
- educational_qual: education status
- call_type: contact communication type
- day: last contact day of the month (numeric)
- mon: last contact month of the year
- dur: last contact duration, in seconds (numeric)
- num_calls: number of contacts performed during this campaign and for this client
- prev_outcome: outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success")

## Output Variable (Desired Target)
y - has the client subscribed to the insurance?

## Minimum Requirements
It is not sufficient to just fit a model; the model must be analyzed to find the important factors that contribute to the conversion rate. AUROC must be used as a metric to evaluate the performance of the models.

## Introduction
This project was completed and presented as a team as part of the final project for the Knowledge Discovery and Data Mining (CS-513B) course by Professor Kashayar Dehnad. The goal was to predict whether a client will subscribe to the insurance based on historical marketing data of the insurance company.

## Data Preprocessing
The data was loaded and preprocessed, including handling missing values and encoding categorical features.

## Exploratory Data Analysis
Data visualization and exploratory data analysis were performed to gain meaningful insights into the dataset.

## Model Building
The initial model used was logistic regression and Random Forest, which achieved a good AUROC score. However, to build a more reliable model considering the domain context, a decent F1 score was required.

## Model Evaluation
To compare and tune the models, Pycaret was used, and feature importances were analyzed.

## Conclusion
In conclusion, a machine learning model was built to predict whether a customer will subscribe to the insurance. The model was evaluated using AUROC and F1 scores to ensure performance and reliability.

## Usage
To use the model, you can either deploy it using the Streamlit app or run the Python script locally.

## Author
This project was developed and presented by Supreeth Hassan Ravindra, Yash Deshpande and Thejesh Ravikumar.
