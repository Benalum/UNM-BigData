[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/COoakvX0)
[![Work in MakeCode](https://classroom.github.com/assets/work-in-make-code-8824cc13a1a3f34ffcd245c82f0ae96fdae6b7d554b6539aec3a03a70825519c.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16034184&assignment_repo_type=AssignmentRepo)

In this lab, you will perform time series analysis on COVID-19 data using locally weighted regression techniques. You will implement and explore both Locally Weighted Linear Regression (LWLR) and Locally Weighted Polynomial Regression (LWPR) using a sliding window approach. The aim is to understand how these regression techniques can be used to forecast COVID-19 cases by fitting localized models to the data.


### Dataset
You will be using the COVID-19 dataset provided by Our World in Data:

Dataset URL: owid-covid-data.csv
Make sure to focus on the following columns:

* date: Date of the record.
* new_cases: Number of new COVID-19 cases reported.
* new_deaths: Number of new COVID-19 deaths reported.

For this lab, we will analyze data for a specific country (e.g., Germany, United States).

### Lab Overview

#### Data Loading and Preprocessing:

* Load the dataset from the provided URL using pandas.
* Filter the dataset for a specific country (e.g., the United States).
* Convert the date column to a datetime format and set it as the index.
* Fill any missing values appropriately to ensure a smooth analysis.

#### Locally Weighted Linear Regression (LWLR):

* Define a function for the Gaussian kernel to calculate weights.
* Implement the function for locally weighted linear regression, adding a regularization term to prevent singular matrices.
* Perform forecasting using a sliding window approach.

#### Locally Weighted Polynomial Regression (LWPR):

* Define a function to transform features into polynomial form.
* Implement the function for locally weighted polynomial regression with error handling for singular matrices.
* Apply the sliding window approach for this regression as well.


#### TODO tasks

* Experiment with different window sizes and kernel bandwidths to see their effects on the forecast accuracy.
* Identfy anomalies but in the sliding window version of the code.
* Apply locally weighted regression to other columns (e.g., new_deaths) and observe any differences in patterns.
* Use the seasonality decomposition to remove it from the data, repeat the forecasting experiment with LWLR and LWPR, observe and discuss advantages or disadvantages of removing seasonality.
* Plot the new data along with the locally weighted linear and polynomial regression forecasts.
* Compare the locally weighted models to global models (e.g., regular linear regression).
* Comment and document your notebook


### Prerequisites
Before starting this lab, ensure you have the following Python libraries installed:

* pandas
* numpy
* matplotlib
* scikit-learn