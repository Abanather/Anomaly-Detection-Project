# Anomaly-Detection-Project

## Overview
This repository contains an anomaly detection analysis project. The goal of this project is to analyze synthetic authentication data to identify suspicious authentication attempts and gain insights into anomalous authentication activities. 
The analysis includes data cleaning, exploratory data analysis (EDA), and the implementation of an anomaly detection model.

## Dataset

The dataset used in this project consists of four CSV files:
- auth.csv: Contains authentication events data.
- devices.csv: Contains device information.
- orgs.csv: Contains organization data.
- users.csv: Contains user information.

## Analysis
The analysis includes the following steps:

Data cleaning and preparation.
Exploratory data analysis (EDA) to understand the dataset.
Visualization of success and failure rates, authentication methods, countries, devices, operating systems, and organization types.
Implementation of an Isolation Forest model for anomaly detection.
Evaluation of the model's performance using accuracy, precision, recall, and F1-score.

## Results
The results of the analysis are summarized in the Anomaly Detection.ipynb notebook. Here are key findings:

Success rate of authentication attempts is approximately 60.17%, with a failure rate of 39.83%.
The 'sms' authentication method had the highest number of failed attempts, indicating potential security concerns.
Mobile devices and iOS operating systems are most commonly used for authentication.
The Isolation Forest model achieved a high recall and F1-score in detecting anomalies, suggesting its effectiveness in identifying potential security threats.
