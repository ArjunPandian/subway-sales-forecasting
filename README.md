# Subway Sales Forecasting

## About
This is my University of London CM3070 Final Year Project:
- Name: `Arjun S/O Pandian`
- Student Number: `210485925`
- Supervisor: `Chew Jee Loong`

## Prerequisite
- Python version 3.11.8 is installed.
- Download and extract the dataset from Kaggle: [Corporación Favorita Grocery Sales Forecasting](https://www.kaggle.com/c/favorita-grocery-sales-forecasting/data)
- Optional (as `1 - Prep.ipynb` will check for and install dependencies):
    ```shell
    pip install -r requirements.txt
    ```

## Directory Structure
- 1 - Prep.ipynb [^1]
- 2 - RF.ipynb [^1]
- 3 - ARIMA.ipynb [^1]
- 4 - NN.ipynb [^1]
- family.csv [^1]
- holidays_events.csv [^2]
- items.csv [^2]
- oil.csv [^2]
- README.md [^1] [^3]
- requirements.txt [^1] [^3]
- sample_submission.csv [^2] [^3]
- stores.csv [^2]
- test.csv [^2] [^3]
- train.csv[^2]
- transactions.csv [^2]
- X_test.csv [^4]
- X_train.csv [^4]
- y_test.csv [^4]
- y_train.csv [^4]

## Instructions
1. Run all cells in `1 - Prep.ipynb`. This will generate `X_train.csv`, `y_train.csv`, `X_test.csv` and `y_test.csv` files.
   > :watch: This file takes about 20 minutes to run.
2. Run all cells in `2 - RF.ipynb`.
   > :watch: This file takes about 3 hours to run.
3. Run all cells in `3 - ARIMA.ipynb`.
   > :watch: This file takes about 1 hour to run.
4. Run all cells in `4 - NN.ipynb`.
   > :watch: This file takes about 13 hours to run (10 hours for initial 10% data and 3 hours for final best param 100% data).

[^1]: Downloaded from current GitHub repo: [Subway Sales Forecasting](https://github.com/ArjunPandian/subway-sales-forecasting)
[^2]: Downloaded from Kaggle: [Corporación Favorita Grocery Sales Forecasting](https://www.kaggle.com/c/favorita-grocery-sales-forecasting/data)
[^3]: Not required for running project
[^4]: Will be generate by project
