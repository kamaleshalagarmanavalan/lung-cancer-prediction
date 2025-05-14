# lung-cancer-prediction
This repository is created to share my experience of working in google colab notebook for prediction of lung cancer using machine learning with lung cancer dataset which is collected from kaggle.

# Dataset Description
This dataset is collected from https://www.kaggle.com/code/irfanmansuri/lung-cancer/notebook

## Dataset Overview
1. Total Entries: 59
2. Total Columns: 7
3. Purpose: Appears to be for classifying lung cancer risk based on lifestyle and demographic factors.

## Columns Description
| Column    | Type   | Description                                                             |
| --------- | ------ | ----------------------------------------------------------------------- |
| `Name`    | object | First name of the individual (not relevant for modeling)                |
| `Surname` | object | Last name of the individual (not relevant for modeling)                 |
| `Age`     | int64  | Age of the individual (18 to 77 years)                                  |
| `Smokes`  | int64  | Smoking level (number of cigarettes per day or frequency)               |
| `AreaQ`   | int64  | Environmental quality index (possibly pollution or risk exposure score) |
| `Alkhol`  | int64  | Alcohol consumption level (scale 0–8)                                   |
| `Result`  | int64  | Target variable: **1 = Lung cancer detected**, **0 = No lung cancer**   |

## Key Statistics:
1. Age: Mean = 42.6, Min = 18, Max = 77
2. Smokes: Mean = 15.1, Min = 0, Max = 34
3. AreaQ: Mean = 5.2, Range = 1 to 10
4. Alkhol: Mean = 3.2, Range = 0 to 8
5. Result: About 47% of entries are positive (1), indicating lung cancer


