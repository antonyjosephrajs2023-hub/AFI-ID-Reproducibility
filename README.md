# AFI-ID-Reproducibility

Pipeline:
1. Data preprocessing
2. AFI feature selection
3. Logistic Regression
4. Extra Trees
5. XGBoost
6. Attention-BiLSTM stacking

Run:

python AFI_ID.py

Environment:
Python 3.10

Dataset:
Place CICIDS2017 CSV files inside ./dataset/

Output:
- Selected features
- Training logs
- Classification metrics
- Accuracy, MCC, Kappa, Log Loss

Reproducibility:
Random seed = 42
