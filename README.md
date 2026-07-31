# Heart Rate Prediction using Linear Regression

## Overview

This project uses **Linear Regression** and **Multiple Linear Regression** to predict a patient's maximum heart rate (`thalach`) using the Heart Disease dataset.

## Dataset

* **File:** `heart (1).csv`
* **Target Variable:** `thalach`
* **Features Used:**

  * **Simple Linear Regression:** `age`
  * **Multiple Linear Regression:** `age`, `trestbps`, `chol`

## Objectives

* Predict maximum heart rate (`thalach`) using Linear Regression.
* Compare Simple and Multiple Linear Regression models.
* Evaluate model performance using Mean Squared Error (MSE).

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib

## Project Structure

```
├── heart (1).csv
├── simple_linear_regression.py
├── multiple_linear_regression.py
└── README.md
```

## Steps Performed

### Simple Linear Regression

* Loaded the dataset
* Selected `age` as the independent variable
* Trained a Linear Regression model
* Plotted the regression line
* Displayed slope, intercept, and MSE

### Multiple Linear Regression

* Loaded the dataset
* Selected `age`, `trestbps`, and `chol` as independent variables
* Trained a Multiple Linear Regression model
* Displayed coefficients, intercept, and MSE

## Results

* The Multiple Linear Regression model achieved better prediction accuracy.
* Adding more relevant features reduced the Mean Squared Error (MSE).
* The model can assist in estimating a patient's maximum heart rate, supporting early heart health risk assessment.

## How to Run

1. Install the required libraries:

```
pip install pandas scikit-learn matplotlib
```

2. Place `heart (1).csv` in the project folder.

3. Run the Python scripts:

```
python simple_linear_regression.py
```

or

```
python multiple_linear_regression.py
```

## Author

ADWAITH KRISHNA M H
