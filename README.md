# Golfing_Around

The Golfing_Around project aims to analyze the data of professional golf players from the PGA Tour between 2011 and 2018. Its primary objective is to build machine learning models to predict a player's likelihood of victory and their financial gains in a particular year. By leveraging accurate predictive models, this project seeks to offer valuable insights into the performance and earnings of professional golfers.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Data](#data)
- [Features](#features)
- [Models](#models)
- [Contributing](#contributing)


## Introduction
The PGA Tour showcases the thrilling and captivating world of golf. With each swing and putt, spectators eagerly await to discover if a player's exceptional performance will lead to victory or not, creating an irresistible desire to unravel the outcome. By analyzing historical player records from the PGA Tour, this project aims to build effective machine learning models to provide valuable insights into a golfer's performance and earnings, for both golf enthusiasts and industry professionals.

## Installation
To use this project, clone the repository and install the required dependencies using the following command:

pip install -r requirements.txt

## Data
This project utilizes the PGA Tour data from 2011 to 2018, containing various features such as player statistics, tournament information and the money earned by the golfers. It is important to ensure that the dataset is properly cleaned and prepared before running the project. The `pgaTourData.csv` file contains the dataset used for analysis and prediction.

## Features
- Data Preprocessing and Cleaning: This project includes modules to preprocess and clean the PGA Tour data, ensuring that it is ready for analysis.
- Exploratory Data Analysis: Various statistical and visual techniques are employed to gain insights into the data and identify patterns or correlations.
- Machine Learning Models: The project employs machine learning algorithms to predict a PGA golfer's victory and earnings based on historical data.
- Evaluation and Metrics: Different evaluation metrics are used to assess the performance of the machine learning models and measure their predictive accuracy.

## Models
This project employs several ML classification models to predict a golfer's win in the tournament, including:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier

This project also employs ML regression models to predict a golfer's financial gains in the tournament, including:
- Linear Regression
- Randon Forest Regressor 

The performance of each model is evaluated using appropriate metrics so that the best performing model can be used for future predictions.

## Contributing
Contributions to this project are welcome. If you find any bugs, have feature requests or want to contribute improvements, please submit an issue or a pull request. 
