# Email Spam Detection with Machine Learning

Author: Syed Aon Muhammad Kazmi

Data: UCI SMS Spam Collection, https://archive.ics.uci.edu/dataset/228/sms+spam+collection. The assignment allows this dataset, but it contains SMS messages, not emails. Results therefore support an SMS spam classifier, not validated email performance.

## Run
From the OIBSIP root: `pip install -r requirements.txt`. Open this folder’s `analysis.ipynb` in Jupyter or VS Code and Run All. Paths are relative to this project folder. The public notebook is source-only. Aggregate evaluation results and charts are in `outputs/`; run the notebook locally to reproduce them. The raw dataset and executed HTML report are excluded from public GitHub.

## Deliverables
- `analysis.ipynb`: source code for EDA, explanations, charts and evaluation
- `outputs/`: exported charts and result tables
- Raw SMS messages are excluded from GitHub; the notebook downloads the public UCI dataset when run.

See the root SUBMISSION_CHECKLIST.md for demo and submission requirements.

## Verified results
Logistic Regression wins training CV spam F1 (0.908) and reaches held-out spam F1 0.902, precision 0.891 and recall 0.913. Naive Bayes has higher precision (0.989) but lower recall (0.730). The selected model catches more spam at the cost of more false positives.
