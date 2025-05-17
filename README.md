# Prognosis Prediction

This project focuses on classifying diseases based on patient symptoms using machine learning techniques.

## Overview

The dataset contains medical symptoms and their corresponding disease diagnoses. The goal is to build a model that can accurately predict a patient's disease given their symptoms.

## Dataset

- The data consists of two CSV files: `Training.csv` and `Testing.csv`.
- Each row represents a patient with various symptom indicators (e.g., itching, skin rash, headache) as features.
- The target variable is the `prognosis` column, which indicates the diagnosed disease.

## Approach

- Data preprocessing includes encoding categorical labels and preparing the feature set.
- A neural network model is built using TensorFlow/Keras for multi-class classification.

View all the work in the notebook: [PrognosisPrediction.ipynb](./PrognosisPrediction.ipynb)



