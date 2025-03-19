# Bank Term Deposit Predictor

A machine learning model that predicts whether a client will subscribe to a bank term deposit based on demographic, economic, and campaign data.

## Project Overview

This project uses the UCI Bank Marketing dataset to develop and deploy a Random Forest classifier that predicts customer subscription to term deposits. The model analyzes various features including customer demographics, economic indicators, and marketing campaign data to make accurate predictions.

## Features

- **Data Analysis**: Comprehensive exploration of the bank marketing dataset
- **Machine Learning Model**: Random Forest classifier with hyperparameter optimization
- **Performance**: Achieved ROC-AUC of 0.750 and F1-score of 0.90 for the subscribed class
- **Interactive Web Application**: Streamlit-based interface for real-time predictions

## Live Demo

Try the deployed model: [Bank Term Deposit Predictor](https://banktermpredict-jdv3pnrdwvwhbgq6j2tmgx.streamlit.app/)

## Dataset

The dataset contains 4119 instances with 20 input features, including:
- Demographic: age, job type, marital status, education
- Economic: employment variation rate, consumer price index, Euribor 3-month rate
- Campaign: number of contacts, days since last contact

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/bank-term-deposit-predictor.git

# Navigate to the project directory
cd bank-term-deposit-predictor

# Install dependencies
pip install -r requirements.txt
