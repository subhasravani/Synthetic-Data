# Fraud Detection with Synthetic Data

## Project Overview

This project focuses on designing and implementing a fraud detection system using synthetic data. It demonstrates the creation of a realistic synthetic dataset simulating financial transactions, training machine learning models to identify fraudulent activities, and evaluating their performance.

## Key Objectives

- Generate a synthetic dataset that mirrors real-world transaction patterns.
- Develop and train machine learning models for fraud detection.
- Address class imbalance issues using techniques like SMOTE.
- Evaluate model performance using relevant metrics.
- Showcase data science skills in feature engineering, model selection, and evaluation.

## Dataset

The synthetic dataset includes features like transaction amount, merchant category, time of day, location, weekend indicator, and previous transaction history. Fraudulent transactions are introduced with a controlled probability and correlated with specific features to enhance realism.

## Model Training and Evaluation

The project explores various machine learning models, including:

- Random Forest
- XGBoost
- Logistic Regression
- Support Vector Machine
- Neural Network

These models are trained and evaluated on the synthetic dataset, with a focus on achieving high accuracy and minimizing false negatives (missed fraud cases).

## Ensemble Method

An ensemble approach using a Voting Classifier is implemented to combine the predictions of individual models, potentially leading to improved performance.

## Results

The results section presents the performance metrics of different models, including precision, recall, F1-score, and ROC AUC. The ensemble method demonstrates superior performance compared to individual models.

## Deployment

The final model is deployed using Flask, creating a simple API for fraud detection predictions.

## Usage

To use the fraud detection system, send a POST request to the `/predict` endpoint with the transaction features as JSON data. The API will return a prediction indicating whether the transaction is fraudulent (1) or not (0).

## Future Enhancements

- Explore more advanced synthetic data generation techniques.
- Implement hyperparameter tuning for further performance optimization.
- Integrate the model into a real-world system for fraud prevention.
