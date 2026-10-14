# Iris Flower Classification

Author: Syed Aon Muhammad Kazmi

Data: built-in scikit-learn Iris dataset, https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html. Measurements are in cm; this small benchmark does not establish real-world performance.

## Run
From the OIBSIP root: `pip install -r requirements.txt`. Open this folder’s `analysis.ipynb` in Jupyter or VS Code and Run All. Paths are relative to this project folder. The notebook includes executed results; `report.html` is a browser-readable copy.

## Deliverables
- `analysis.ipynb`: EDA, explanations, charts and evaluation
- `outputs/`: exported charts and result tables
- `data/`: dataset where required

See the root SUBMISSION_CHECKLIST.md for demo and submission requirements.

## Verified results
Both classifiers achieved 95.83% mean training CV accuracy and 93.33% held-out accuracy. Logistic Regression is selected by the stated simplicity tie-break. Neither classifier is demonstrably superior on this split.
