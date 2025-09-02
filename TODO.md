# TODO — Titanic Survivor Predictor


## High Priority
-  Convert exploratory code into a clean notebook under `notebooks/`.
-  Add target/feature split (`y = Survived`, `X = rest`) post‑pipeline.
-  Implement baselines (LogReg, DecisionTree) and record metrics.
-  Create `assets/` plots: confusion matrix, classification report heatmap.
-  Save trained models with `joblib` and version them (`models/`).


## Medium Priority
-  Add cross‑validation and basic hyperparameter searches.
-  Feature engineering: `FamilySize`, `IsAlone`, `Title` from `Name`.
-  Handle missing `Embarked` values explicitly.
-  Improve categorical encoding: use a single fitted encoder within a `ColumnTransformer`.
-  Separate numeric/categorical pipelines.


## Low Priority
-  Unit tests for transformers in `tests/`.
-  Add `pre-commit` hooks (black, isort, flake8).
-  Add CI (GitHub Actions) to run tests and linting.
-  Write a short blog‑style `NOTES.md` on lessons learned.
