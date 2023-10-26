# California Housing Dataset Regression Model
This README file provides instructions for using two Python notebook scripts to train a regression model on the California Housing dataset and estimate housing prices based on several features. The first script downloads the dataset and trains the model, while the second script calls a Lambda AWS function to get the estimated price based on the fitted model.

## Prerequisites

    Python 3.x
    AWS account with Lambda function permissions

## Installation

    Clone the repository to your local machine.

## Usage
 - Script 1: California_Housing_Model.ipynb

This script downloads the California Housing dataset and trains a regression model to estimate housing prices based on several features.

    Open train_model.py in your preferred Python notebook editor.
    Run the script.

The script will download the California Housing dataset using scikit-learn and split it into training and testing sets. It will then train a regression model on the training set and evaluate its performance on the testing set. Finally, it will save the fitted model to a file.

 - Script 2: CallLambda.ipynb

This script calls a Lambda AWS function to get the estimated price based on the fitted model.

    Open CallLambda.ipynb in your preferred Python notebook editor.
    Replace the variable containing the features for which you want to estimate the housing price.
    Run the script.

The script will call the specified Lambda function with the provided payload and return the estimated housing price.
 
