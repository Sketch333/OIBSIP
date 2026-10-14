# OIBSIP: Data Science Projects

Author: Syed Aon Muhammad Kazmi

Five projects covering classification, historical unemployment EDA, used-car regression, SMS spam detection and advertising-based sales regression. Each folder contains a notebook, README and outputs. Four projects also include HTML reports; the spam project uses a source-only notebook and downloads its raw dataset locally.

## Setup
Python 3.12 recommended. `pip install -r requirements.txt`. Open each notebook with its project directory as the working directory. Car, unemployment and advertising datasets are bundled; Iris is built into scikit-learn. The spam notebook downloads the public UCI SMS dataset locally; raw SMS messages are excluded from the repository.

Model selection uses training-only cross-validation. Preprocessing is inside pipelines. Metrics reflect historical held-out samples, not deployment guarantees. Review and understand the notebooks before recording demos.
