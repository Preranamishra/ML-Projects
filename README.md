# NYC Taxi Fare Prediction
## Overview

This project aims to predict additional taxi fare charges for yellow cabs in New York City using machine learning techniques. By analyzing trip data from February 2016, the goal is to develop a model that determines whether extra charges (such as rush hour or overnight fees) will be applied to a fare.
Features

    Data Cleaning: Preprocessing of raw trip data to ensure quality and usability.
    Feature Extraction: Transforming datetime columns into meaningful features for the model.
    Model Development: Implementing a binary classification approach to predict the target variable, Extra, indicating the application of additional charges.
    Model Evaluation: Initial accuracy of 80%, with plans for further optimization.

## Future Work

    Hyperparameter Tuning: Use Grid Search to optimize model parameters for improved accuracy.
    Feature Analysis: Conduct in-depth analysis to identify and enhance the most influential features.

## Dataset

The dataset used in this project consists of yellow taxi trip records from New York City for February 2016, provided by the NYC Taxi and Limousine Commission (TLC).
Installation

    Clone the repository:

    bash

git clone https://github.com/yourusername/nyc-taxi-fare-prediction.git

Navigate to the project directory:

bash

cd nyc-taxi-fare-prediction

Install the required packages:

bash

    pip install -r requirements.txt

Usage

Run the main script to start the model training and prediction process:

bash

python main.py

License
