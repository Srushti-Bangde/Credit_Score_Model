# Credit_Score_Model

## Overview

This repository contains a credit score model developed using machine learning techniques. The model aims to predict whether a credit card user will default on their payment next month based on various features provided in the dataset.

## Features

- Uses a Random Forest Classifier to predict credit card defaults.
- Utilizes a Gradio interface to create an interactive web-based user interface for predictions.

## Data

The model is trained on the [Default of Credit Card Clients Dataset](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients) from UCI Machine Learning Repository.

## Usage

1. Install the required Python libraries using the following command:
   ```
   pip install -r requirements.txt
   ```

2. Run the `credit_score_model.py` script to launch the Gradio interface.
   ```
   python credit_score_model.py
   ```

3. Input the required details in the interface, such as gender, education, marital status, age, credit limit, bill amount, and payment amount.

4. The model will predict whether the credit card user will default or not and display the result on the interface.

## Model Evaluation

The model's performance can be evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC AUC score. These metrics provide insights into the model's ability to predict defaults accurately.

## Examples

Here are a few example input sets that you can try in the Gradio interface:

- Gender: Male
  Education: University
  Marital Status: Married
  Age: 30
  Credit Limit: 5000
  Bill Amount (Last Month): 2000
  Payment Amount (Last Month): 2500

- Gender: Female
  Education: Graduate School
  Marital Status: Single
  Age: 25
  Credit Limit: 10000
  Bill Amount (Last Month): 500
  Payment Amount (Last Month): 500

- Gender: Male
  Education: High School
  Marital Status: Married
  Age: 40
  Credit Limit: 15000
  Bill Amount (Last Month): 8000
  Payment Amount (Last Month): 7000

- Gender: Female
  Education: Others
  Marital Status: Single
  Age: 22
  Credit Limit: 3000
  Bill Amount (Last Month): 100
  Payment Amount (Last Month): 150
