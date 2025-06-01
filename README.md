# python-linear-regression-demo-by-Dr-BERNARD
A simple linear regression experiment using scikit-learn and Matplotlib to predict price based on area
# Simple Linear Regression Experiment 📈

This repository contains a Python script and a Jupyter Notebook that demonstrate a simple linear regression model. The experiment aims to predict a dependent variable (e.g., 'price') based on an independent variable (e.g., 'area') using a dataset.

## 📝 Description

The code performs the following steps:
1.  Imports necessary libraries: `scikit-learn` for the regression model, `numpy` for numerical operations, and `matplotlib` for plotting.
2.  Defines a sample dataset for the independent variable (X) and the dependent variable (Y).
3.  Fits a linear regression model to the data.
4.  Calculates and prints the model's coefficients (slope and intercept).
5.  Visualizes the original data points with a scatter plot and overlays the fitted regression line.

## 🛠️ Technologies Used

* Python 3
* Scikit-learn
* NumPy
* Matplotlib

## 💾 Data

The dataset used is:
* X (Area): `[121, 125, 131, 141, 152, 161]`
* Y (Price): `[300, 350, 425, 405, 496, 517]`

## 📊 Results

The script outputs:
* The **slope** (coefficient) of the regression line.
* The **intercept** of the regression line.
* A plot showing the data points and the regression line.

## 🚀 How to Run

1.  Clone this repository: `git clone https://github.com/Dr-Bernard/python-linear-regression-demo-by-Dr-BERNARD.git`
2.  Navigate to the directory: `cd python-linear-regression-demo-by-Dr-BERNARD`
3.  If it's a Python script (`.py`): `python your_script_name.py`
4.  If it's a Jupyter Notebook (`.ipynb`): Open it with Jupyter Notebook or JupyterLab: `jupyter notebook your_notebook_name.ipynb`

Make sure you have the required libraries installed:
```bash
pip install numpy scikit-learn matplotlib
