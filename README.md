Traffic Congestion Level Prediction Using Random Forest and Gradient-Boosted Trees

Project Overview

Traffic congestion occurs when the number of vehicles and traffic demand on roads affect normal traffic movement, resulting in slower movement and increased travel time.

This project aims to develop a machine learning system for predicting traffic congestion levels using historical traffic data. The project uses Random Forest and Gradient-Boosted Trees as the main supervised learning algorithms.

The project follows the machine learning lifecycle:

Data Collection → Data Cleaning → Feature Engineering → Model Training → Model Evaluation → Prediction

Project Objectives

Collect and prepare a large traffic dataset.

Perform data cleaning and preprocessing.

Analyze traffic-related data.

Create features required for congestion prediction.

Create a congestion-level target variable.

Train a Random Forest model.

Train a Gradient-Boosted Trees model.

Evaluate and compare the models using suitable classification metrics.

Use the trained model to predict traffic congestion levels.

Dataset

The project uses the PeMSD7 traffic dataset.

The main cleaned dataset used in the current project is:

PeMSD7_V_1026.csv

The dataset contains traffic-speed measurements from 1,026 traffic sensors.

Current cleaned dataset information:

Rows: 12,672

Columns: 1,026

Missing values: 0

Duplicate rows: 0

The project also maintains a cleaning report documenting the data-cleaning results.

Data Cleaning

The dataset is checked and prepared before machine learning.

The cleaning stage includes:

Checking the dataset structure

Checking missing values

Checking duplicate records

Checking data values

Preparing the cleaned dataset for further machine learning processing

After cleaning, the dataset is used as the input for the next stages of the project.

Machine Learning Approach

1. Feature Engineering

Traffic data will be transformed into suitable features for machine learning. Time-related and traffic-related information will be prepared where applicable.

2. Target Variable

A Congestion_Level target variable will be created for classification.

The target will represent different traffic congestion levels such as:

Low

Medium

High

The exact classification rule will be defined during the feature-engineering stage.

3. Random Forest

Random Forest is a tree-based supervised learning algorithm that combines multiple decision trees to make predictions.

4. Gradient-Boosted Trees

Gradient-Boosted Trees build decision trees sequentially, with each new tree helping to reduce errors made by previous trees.

Model Evaluation

The trained models will be evaluated using appropriate classification metrics, including:

Accuracy

Precision

Recall

F1-score

ROC-AUC, where applicable

The evaluation results will be used to understand the performance of the two models.

Project Workflow

Traffic Dataset
      ↓
Data Cleaning
      ↓
Cleaned Dataset
      ↓
Feature Engineering
      ↓
Create Congestion Level
      ↓
Train/Test Split
      ↓
Random Forest
      ↓
Gradient-Boosted Trees
      ↓
Model Evaluation
      ↓
Traffic Congestion Prediction

Technologies Used

Python 3.x

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook / VS Code

Course Outcome Alignment

CO1

Analyze the machine learning lifecycle from data preparation through model prediction.

CO2

Apply supervised-learning concepts and preprocessing techniques.

CO3

Apply tree-based supervised-learning models including Random Forest and Gradient-Boosted Trees.

CO5

Evaluate model performance using classification metrics and appropriate train/test methodology.

CO6

Apply basic machine-learning engineering practices during the project implementation.

Project Status

Completed

Project topic and objective

Traffic dataset selection

Dataset extraction

Data cleaning

Cleaned dataset preparation

Cleaning report

Next Steps

Explore the cleaned dataset

Perform feature engineering

Create the congestion-level target

Prepare training and testing data

Train Random Forest

Train Gradient-Boosted Trees

Evaluate the models

Generate congestion predictions

Team

Course: Machine Learning

Department: Computer Science and Engineering

Academic Year: 2026–27

Project Title

Traffic Congestion Level Prediction Using Random Forest and Gradient-Boosted Trees
