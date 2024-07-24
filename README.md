# **Customer Income Prediction Model**

## **Overview**

This repository contains a machine learning model that predicts the income of a customer based on various parameters such as spending on groceries, food, and other categories such as number of children, marital status.<br>
<br>
The model is designed to estimate a customer’s income by providing a range of predicted values rather than a single figure. 
Specifically, it generates a prediction interval that includes a lower bound, set at the 7.5th percentile, and an upper bound, set at the 92.5th percentile. 
This means that the actual income of a customer is expected to fall within this range with a high level of confidence, accounting for uncertainties and variations in the data.

## **Model Details**

* **Model Type:** CatBoost <br>
* **Accuracy:** 85% on the training set, 82% on the cross-validation set <br>
* **Prediction:** Income range with lower and upper bounds <br>

## **Data**

The Dataset was originally intended for classifying customers into various segments based on their shopping habits and expenditure but has been adapted for prediction of their income.<br>
The Dataset used for this model is sourced from Kaggle and was originally created by Akash Patel by utilizing data provided by Dr. Omar Romero-Hernandez.<br>

## **Installation**

To use this model, follow these steps:

1) Clone the repository:
`git clone https://github.com/DC-0001/Income_Predictor.git`

2) Navigate to the project directory:
` cd Income_Predictor `

3) Install the required dependencies:
`pip install -r Requirements.txt`


