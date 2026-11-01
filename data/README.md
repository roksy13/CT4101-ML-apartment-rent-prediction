## Apartment for Rent Classified

## Dataset

This project uses the Apartment for Rent Classified dataset from the UCI Machine Learning Repository.

- Dataset: Apartment for Rent Classified
- Dataset version: 10K
- Source: UCI Machine Learning Repository
- Licence: Creative Commons Attribution 4.0 International (CC BY 4.0) license
- DOI: 10.24432/C5X623

The 10K version of the dataset is used for this project to provide a sufficiently large dataset while keeping computation manageable.

The raw CSV is not included in this repository. Download the dataset
from the source above, extract the archive, and place
apartments_for_rent_classified_10K.csv inside the data/ directory.

The CSV uses a semicolon separator and Latin-1 encoding.

## Project question
Can monthly apartment rental prices be predicted using property
characteristics and location information?

This is a supervised regression project predicting advertised monthly
rent in USD.

## Setup
The project was developed using Python 3.11.9.

From the project root, run:

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

## Running the notebooks
From the project root, run:

```powershell
cd notebooks
..\.venv\Scripts\python.exe -m jupyterlab
```

Open each notebook, select the project environment as its kernel,
and run all cells from top to bottom:

1. 02_1_data_and_baseline.ipynb — data audit.
2. 02_2_data_and_baseline.ipynb — preparation, evaluation and baseline.

Each notebook loads the dataset independently.
01_data_exporing.ipynb contains the earlier Milestone 1 exploration.

## Repository
https://github.com/roksy13/CT4101-ML-apartment-rent-prediction
## Assistance declaration
- Lecture slides were used for data preparation, evaluation and modelling concepts
- https://scikit-learn.org/1.9/modules/generated/sklearn.compose.ColumnTransformer.html
Consulted to understand how different preprocessing pipelines are applied to numerical and categorical columns.