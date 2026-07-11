# FinNova Risk Prediction

This project predicts risky financial transactions from an extremely
imbalanced dataset.

## Dataset

- 61,835 training transactions
- 28 anonymized features
- Transaction value feature
- Binary target: Risk_Flag
- Risky transactions are approximately 0.2%

## Approach

- Exploratory data analysis
- Missing and duplicate value analysis
- Skewness and outlier analysis
- Stratified cross-validation
- Imbalance-aware machine learning
- Threshold optimization for F1 score
- AUC-PR based model evaluation

## Validation Results

- OOF AUC-PR: 0.8694
- ROC-AUC: 0.9580
- Best F1 Score: 0.8819

## Files

- `finnova_final_solution_fixed.ipynb`: Complete solution
- `submission_fixed.csv`: Final binary predictions

## Run

Place the competition train and test files in the notebook directory:

```text
finnova_train.csv
finnova_test.csv
