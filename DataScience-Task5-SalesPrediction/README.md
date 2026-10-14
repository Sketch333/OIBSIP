# Sales Prediction Using Python

Author: Syed Aon Muhammad Kazmi

Data: classic Advertising dataset, https://www.statlearning.com/s/Advertising.csv. Advertising spends are commonly reported in thousands of dollars and sales in thousands of units. Associations in this dataset do not establish causal advertising returns.

## Run
From the OIBSIP root: `pip install -r requirements.txt`. Open this folder’s `analysis.ipynb` in Jupyter or VS Code and Run All. Paths are relative to this project folder. The notebook includes executed results; `report.html` is a browser-readable copy.

## Deliverables
- `analysis.ipynb`: EDA, explanations, charts and evaluation
- `outputs/`: exported charts and result tables
- `data/`: dataset where required

See the root SUBMISSION_CHECKLIST.md for demo and submission requirements.

## Verified results
Degree-2 Polynomial Regression has training CV RMSE 0.676 and held-out RMSE 0.643, versus 1.782 for the linear baseline. Its held-out R² is 0.987. TV has the largest training permutation importance. Residuals are small overall; inspect the residual chart for local patterns rather than interpreting the high R² as a guarantee.
