# Titanic-Problem

The sinking of the Titanic is one of the most infamous shipwrecks in history.
On April 15, 1912, during her maiden voyage, the widely considered
“unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately,
there weren’t enough lifeboats for everyone onboard, resulting in the death of
1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some
groups of people were more likely to survive than others.

You need to build a predictive model that answers the question: “what sorts of
people were more likely to survive?” using passenger data (ie name, age,
gender, socio-economic class, etc)

## About the Dataset

•Train.csv will contain the details of a subset of the passengers on board
(891 to be exact) and importantly, will reveal whether they survived or not,
also known as the “ground truth”.

• The `test.csv` dataset contains similar information but does not disclose
the “ground truth” for each passenger. It’s your job to predict these
outcomes.

• Using the patterns you find in the train.csv data, predict whether the other
418 passengers on board (found in test.csv) survived.


## Solution Required:

• You should submit a csv file with exactly 418 entries plus a header row.

• The file should have exactly 2 columns:

• PassengerId (sorted in any order)

• Survived (contains your binary predictions: 1 for survived, 0 for deceased)

## This Notebook will show basic examples of:

Data Handling Importing Data with Pandas Cleaning Data Exploring Data through Visualizations with Matplotlib

## Valuation of the Analysis

K-folds cross validation to valuate results locally Output the results from the IPython Notebook to csv file
