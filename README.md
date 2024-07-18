# Customer Churn Prediction using AWS SageMaker

This repository contains the code and resources for a customer churn prediction analysis project. The project is implemented using AWS SageMaker with an XGBoost model, and the data and model are stored in an S3 bucket.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Setup](#setup)
- [Data](#data)
- [Model Training](#model-training)
- [Model Deployment](#model-deployment)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

Customer churn prediction is a critical task for businesses to retain customers and improve customer satisfaction. In this project, we use AWS SageMaker to build and deploy an XGBoost model for predicting customer churn.

## Project Structure


## Setup

1. **Create a Notebook Instance on SageMaker:**
    - Go to the AWS Management Console.
    - Navigate to Amazon SageMaker.
    - Create a new Notebook Instance.

2. **Upload the Notebooks to Jupyter Server:**
    - Once the Notebook Instance is ready, open Jupyter.
    - Upload the `CustomerChurn.ipynb` file to the Jupyter server.

3. **Run the Notebooks:**
    - Open `CustomerChurn.ipynb` and run all cells to download data, train model and deploy the model and make predictions.


## Model Training

The model is trained using the XGBoost algorithm available on AWS SageMaker. The training process is documented in the `CustomerChurn.ipynb` notebook. The trained model is then stored in an S3 bucket.

## Model Deployment

The trained model is deployed using AWS SageMaker, and the deployment process is detailed in the `CustomerChurn.ipynb` notebook. The model endpoint is created to make predictions on new data.

## Results

The performance of the model is evaluated using metrics such as accuracy, precision, recall, and F1-score. The results are discussed in the `CustomerChurn.ipynb` notebook.

## Conclusion

This project demonstrates how to build, train, and deploy a machine learning model for customer churn prediction using AWS SageMaker. The use of AWS services like SageMaker and S3 simplifies the process of model development and deployment.
