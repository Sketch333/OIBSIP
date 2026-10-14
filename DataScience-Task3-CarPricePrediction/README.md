# Car Price Prediction with Machine Learning

Author: Syed Aon Muhammad Kazmi

Data: used-car listings from CarDekho, public mirror https://github.com/chandanverma07/DataSets/blob/master/CAR%20DETAILS%20FROM%20CAR%20DEKHO.csv. Prices are treated as INR; km_driven is distance travelled, not fuel efficiency. Historical listings are not current valuations.

## Run
From the OIBSIP root: `pip install -r requirements.txt`. Open this folder’s `analysis.ipynb` in Jupyter or VS Code and Run All. Paths are relative to this project folder. The notebook includes executed results; `report.html` is a browser-readable copy.

## Deliverables
- `analysis.ipynb`: EDA, explanations, charts and evaluation
- `outputs/`: exported charts and result tables
- `data/`: dataset where required

See the root SUBMISSION_CHECKLIST.md for demo and submission requirements.

## Verified results
Linear Regression narrowly wins mean training CV RMSE (299,460 INR versus 300,079 INR). Random Forest achieves lower held-out RMSE (358,751 versus 384,723 INR) and MAE, but we retain the predeclared training-CV choice rather than select retrospectively on test results. The close CV means and heavy price tail make the ranking uncertain; more folds/seeds and validation data would be needed for a firm winner.
