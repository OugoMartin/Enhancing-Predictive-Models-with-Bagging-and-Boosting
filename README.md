# Bagging and Boosting for Breast Cancer Classification

A machine-learning experiment comparing ensemble classification techniques on breast-cancer diagnostic data.

## Objective
Explore how bagging and boosting can improve or change classification performance relative to a decision-tree-style baseline.

## Dataset
The notebook uses the scikit-learn breast cancer dataset and also contains work with a 569-row breast-cancer CSV containing diagnostic labels and numeric tumor measurements.

## Methods
- Train/test splitting
- Feature scaling
- Decision-tree classification
- Bagging
- AdaBoost
- Accuracy, precision, recall, F1, classification reports, and confusion matrices

## Repository contents
- `Enhancing Predictive Models with Bagging and Boosting` — notebook-formatted JSON saved without an `.ipynb` extension.
- `README.md` — project documentation.

## Known reproducibility issue
The notebook references `data.csv`, but that file is not committed. It also mixes the built-in scikit-learn dataset with the external CSV workflow. A future cleanup should choose one authoritative data source, rename the notebook with an `.ipynb` extension, and rerun the analysis from a clean environment.

## Skills demonstrated
Python · scikit-learn · Ensemble Learning · Bagging · AdaBoost · Classification Metrics

## Author
Martin Ngare
