# AFI-ID Reproducibility Package

This repository contains the implementation of:

AFI-ID: Adaptive Feature Intelligence for Intrusion Detection

## Pipeline

1. Data preprocessing
2. Adaptive Feature Intelligence (AFI)
3. Logistic Regression
4. Extra Trees
5. XGBoost
6. Attention-BiLSTM stacking

## Environment

Python 3.10

## Installation

pip install -r requirements.txt

## Dataset

Download CICIDS2017 and place CSV files inside:

./dataset/

## Run

python AFI_ID.py

## Outputs

- Selected features
- Training logs
- Accuracy
- Precision
- Recall
- F1-score
- MCC
- Cohen's Kappa
- Log Loss

## Reproducibility

Random seed = 42
