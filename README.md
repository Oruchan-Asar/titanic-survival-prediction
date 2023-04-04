# Titanic Survival Prediction

This machine-learning project predicts passengers' survival on the Titanic based on various features such as age, gender, and ticket class. The project is based on the Kaggle Titanic dataset, which contains information about the passengers onboard the Titanic.

## Prerequisites

To run this project, you will need the following installed:

- Python 3.7 or higher
- Jupyter Notebook or any other IDE that supports running Python code

## Installation

To get started, you can clone this repository by running the following command in your terminal:

```
git clone https://github.com/Oruchan-Asar/titanic-survival-prediction
```

Then, navigate to the project directory by running:

```
cd titanic-survival-prediction
```

Open the Jupyter Notebook `titanic-survival-prediction.ipynb`.

Run the notebook cells to reproduce the analysis.

## Data

The data for this project is stored in two CSV files, `train.csv` and `test.csv`, which can be found in the `data` directory. The `train.csv` file contains the data used to train the machine learning model, while the `test.csv` file contains the data used to make predictions.

## Running the Project

To run the project, simply open the `titanic-survival-prediction.ipynb` file in Jupyter Notebook or any other IDE that supports running Python code. You can then run each cell in the notebook to load and preprocess the data, train the machine learning model, and make predictions on the test data.

The final predictions will be stored in a CSV file called `submission.csv`, which will be created in the same directory.

## Conclusion

In conclusion, the best performing model for this dataset was Random Forest, with an accuracy of 76.31%. The feature importance plot showed that the most important features for predicting survival were the passenger class, sex, and age.
