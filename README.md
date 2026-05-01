# Flight-Price-Prediction

**OVERVIEW:**

This project is part of the Machine Learning Practice (MLP) curriculum in the IITM BS Degree program. The goal of this project is to predict the price of flight tickets based on various features provided in the dataset. This was developed as part of Kaggle Assignment-1 for Term-2 in 2025.

**FILES:**

- train.csv - The training set which contains the features and the target

- test.csv - The test set for which the target column is hidden

- sample_submission.csv - A sample submission file in the correct format

**COLUMN DESCRIPTION:**

- airline: Name of the Airline company.
- flight: Information about flight code.
- source: City from which the flight takes off.
- departure: Time period at which the flight takes off.
- stops: Number of stops between source and destination cities.
- arrival: time period at which the flight lands.
- destination: City where the flight lands.
- class: Information about seat class.
- duration: Overall time taken to travel between cities in hours.
- days_left: Number of days between booking and trip dates.
- price: Information about ticket price.

**EVALUATION:**

Submissions are evaluated on r2_score between the observed target and the predicted target.

**SUBMISSION FILE:**

For each ID in the test set, predict a probability for the TARGET variable. The file should contain a header and have the following format:
| id | price |
|---|--------|
| 0 | 2000 |
| 1 | 13500 |
| 2 | 6540 |

This file 'Flight_Price_Prediction' contains all the steps from data loading to prediction submission like preprocessing, EDA, pipelines/column transformers, model building, hyperparameter tuning, insights and accuracy/scores.

Below is the link of the Kaggle Notebook, the competition was organized on Kaggle Platform.
(https://www.kaggle.com/code/nitindixit9841/23f2005404-ka1)
