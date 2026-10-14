# Verified results

## Task 1
Both classifiers achieved 95.83% mean training CV accuracy and 93.33% held-out accuracy. Logistic Regression is selected by the stated simplicity tie-break. Neither classifier is demonstrably superior on this split.

## Task 3
Linear Regression narrowly wins mean training CV RMSE (299,460 INR versus 300,079 INR). Random Forest achieves lower held-out RMSE (358,751 versus 384,723 INR) and MAE, but we retain the predeclared training-CV choice rather than select retrospectively on test results. The close CV means and heavy price tail make the ranking uncertain; more folds/seeds and validation data would be needed for a firm winner.

## Task 4
Logistic Regression wins training CV spam F1 (0.908) and reaches held-out spam F1 0.902, precision 0.891 and recall 0.913. Naive Bayes has higher precision (0.989) but lower recall (0.730). The selected model catches more spam at the cost of more false positives.

## Task 5
Degree-2 Polynomial Regression has training CV RMSE 0.676 and held-out RMSE 0.643, versus 1.782 for the linear baseline. Its held-out R² is 0.987. TV has the largest training permutation importance. Residuals are small overall; inspect the residual chart for local patterns rather than interpreting the high R² as a guarantee.

## Task 2
The highest unweighted regional mean is Tripura (28.35%). The pre-COVID mean is 9.51% and the COVID-period mean is 20.19%, a change of 10.68 percentage points. These are sample means, not official national estimates.

Validation: all code cells executed sequentially in a fresh per-project namespace using Python 3.12. A local kernel transport restriction prevented execution through nbclient; direct execution preserved notebook tables and image outputs. Notebook schemas validated and HTML reports exported.
