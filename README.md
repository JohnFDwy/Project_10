# Project Title
Gold Recovery Optimization with Machine Learning

## Project Overview
This project aims to develop a machine learning prototype for Zyfra, a company specializing in efficiency solutions for heavy industry. The objective is to predict the amount of gold recovered from ore to optimize the production process and eliminate unprofitable parameters. 

## Data Description
The data is organized in three datasets providing detailed information across various stages of gold extraction and purification. The datasets include metrics on the feed particle size distribution and metal concentrations throughout the process.

## Task Statement
The goal is to prepare the datasets for analysis, perform comprehensive data analysis, and develop a machine learning model. The model will predict the gold recovery rates, measured as the sMAPE (symmetric mean absolute percentage error), which is a key indicator of model performance.

## Methodology
- Data Preparation: Cleaning and pre-processing the datasets, addressing missing values, and preparing the data for analysis.
- Data Analysis: Evaluating the particle size distribution, metal concentration, and other relevant factors affecting gold recovery.
Model Development: Building and training a Random Forest model as well as a Dummy Regressor for performance baseline. Cross-validation is employed to assess model accuracy using sMAPE scores.

## Instructions
Prerequisites
- Ensure the following libraries are installed:
- pandas
- matplotlib
- scikit-learn

## Setup and Run
- Clone the repository.
- Prepare your environment and install the necessary dependencies.
- Execute the scripts to preprocess data, perform exploratory data analysis, and train the models.

## Performance Metrics
The model's performance is evaluated primarily through the sMAPE score, comparing it against a baseline Dummy Regressor to highlight improvements.

## Conclusion
The Random Forest model exhibited minimal but notable improvements over the Dummy Regressor baseline. The project demonstrates the feasibility of employing machine learning to enhance industrial efficiency in gold extraction.
