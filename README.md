# Kaggle Competition Submission: Exploring Mental Health Data

This repository contains my solutions and work for the Kaggle competition titled **Exploring Mental Health Data**. The project aims to explore mental health conditions and predict them using Logistic Regression, focusing on data processing and analysis.

## Overview

- **Competition Name**: Exploring Mental Health Data
- **Objective**: The goal is to analyze and predict mental health conditions based on the available dataset. This includes understanding various factors influencing mental health and predicting the likelihood of mental health conditions.
- **Dataset**: The dataset includes various features such as demographic information, symptoms, and survey responses. The data is a combination of categorical, numerical, and textual variables.

## Project Structure

- `data/`: This folder contains the dataset used in the competition.
- `notebooks/`: Jupyter notebooks with detailed steps for data analysis, preprocessing, and model building.
- `models/`: Code for training and evaluating the Logistic Regression model.
- `submission/`: Final predictions and submission files.

## Key Features

### 1. Data Processing & Preprocessing
- **Handling Missing Data**: I applied methods to handle missing values by either filling or removing them based on the context.
- **Categorical Variable Encoding**: Categorical variables were encoded using one-hot encoding to make them usable for machine learning models.
- **Feature Scaling**: Normalized numerical features to improve the performance of the logistic regression model.

### 2. Logistic Regression Model
- Used **Logistic Regression** to predict the likelihood of mental health conditions based on the features available in the dataset.
- The model was trained and tuned to ensure optimal performance using cross-validation.

### 3. Model Evaluation
- Evaluated the Logistic Regression model using metrics like accuracy, precision, recall, and F1-score.

## Installation

To get started, clone the repository and install the required libraries:

```bash
git clone https://github.com/oussamaF01/mental-health-data-kaggle.git
cd mental-health-data-kaggle
