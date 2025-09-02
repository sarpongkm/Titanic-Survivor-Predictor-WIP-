# Titanic Survivor Predictor (WIP)
> Work in Progress — this repo documents my end‑to‑end ML workflow on the Kaggle Titanic dataset. I’m actively building the pipeline, features, and model comparisons.


## Status
- EDA and stratified train/test split
- Custom transformers (Age imputation, categorical encoding, feature dropping)
- scikit‑learn `Pipeline` integration
- Modeling & evaluation (RF/SVM/MLP planned)
- Visualization of metrics (confusion matrix, classification report, ROC)


## Goals
1. Clean, reproducible preprocessing with custom transformers.
2. Solid baselines (LogReg/DecisionTree) → stronger models (RF, SVM, MLP).
3. Transparent evaluation and error analysis.


## Dataset
- **Source:** Kaggle Titanic: Machine Learning from Disaster (`train.csv`)
- Place the CSV at repo root or update the path in the notebook/script.


## Quickstart
### 1) Environment
```bash
python -m venv .venv
source .venv/bin/activate # Windows: .venv\Scripts\activate
pip install -r requirements.txt
