# Lung Cancer Prediction
This repository is created to share my experience of working in google colab notebook for prediction of lung cancer using machine learning with lung cancer dataset which is collected from kaggle. This machine learning model is trained using random forest classifier which is acheived an accuracy of 91.6%.

# Random Forest
A Random Forest is a machine learning algorithm used for classification and regression tasks. It works by combining many decision trees to make better predictions.
Think of it like a group of students (trees) voting on the answer. The final answer is the majority vote. This makes the result more accurate and less biased.

## How it Works
1. Creates many decision trees (like mini models).
2. Each tree is trained on a random subset of the data (this is called "bagging").
3. Each tree makes a prediction.
4. The forest takes a majority vote (for classification) or average (for regression) to decide the final output.

## Example
To predict if a person has lung cancer (Yes = 1, No = 0) based on features like Age, Smoking, Enviroinmental Quality, Alcohol, etc.
1. Tree 1 says: Yes
2. Tree 2 says: No
3. Tree 3 says: Yes
4. Tree 4 says: Yes

Final output = Yes (majority)

## Advantages
1. High accuracy
2. Reduces overfitting (better than a single decision tree)
3. Works well with both numerical and categorical data
4. Can handle missing values and large datasets

## Disadvantages
1. Slower than a single decision tree (because it builds many trees)
2. Not easy to interpret (less transparent than one tree)

## When to Use
1. Classification problems (e.g., disease detection, spam filter)
2. Regression problems (e.g., predicting prices)
3. When you want high accuracy and don’t need deep explanation of how the model works

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

## Key Statistics
1. Age: Mean = 42.6, Min = 18, Max = 77
2. Smokes: Mean = 15.1, Min = 0, Max = 34
3. AreaQ: Mean = 5.2, Range = 1 to 10
4. Alkhol: Mean = 3.2, Range = 0 to 8
5. Result: About 47% of entries are positive (1), indicating lung cancer


