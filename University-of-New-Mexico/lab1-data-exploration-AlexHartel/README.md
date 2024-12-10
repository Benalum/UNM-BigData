[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/sqCRsL65)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15702051&assignment_repo_type=AssignmentRepo)
# CS467567-Lab1


# README

## Data exploration and data processing

### Overview

This repository contains Python scripts for Lab 1, which is focused on exploring and analyzing COVID-19 datasets. The lab is divided into two parts: Data Exploration and Data Cleaning/Processing. The datasets used in this lab are sourced from [Our World in Data](https://covid.ourworldindata.org/) and [Johns Hopkins University CSSE](https://github.com/CSSEGISandData/COVID-19).

### Prerequisites

Ensure you have Python installed, along with the required libraries:

- pandas

You can install the required libraries using pip:

```bash
pip install pandas
```

### Part 1: Data Exploration

In this section, we load a global COVID-19 dataset and perform various exploratory data analysis tasks, including:

- Displaying the first few rows and columns of the dataset.
- Descriptive statistics and information about the dataset.
- Checking for missing values and duplicated rows.
- Displaying unique values for specific columns.
- Selecting specific rows and columns for more detailed inspection.
- Computing and displaying correlation matrices for specific countries.

### Part 2: Data Cleaning and Processing

In this section, we:

- Load the COVID-19 time series datasets for confirmed cases and deaths from Johns Hopkins University.
- Handle missing values by either dropping them or filling them with zeros.
- Rename columns for consistency and convert date columns to a `datetime` format.
- Reshape the dataset to a long format using `melt` for easier analysis.
- Merge the confirmed cases dataset with the deaths dataset.
- Calculate daily new cases and deaths.
- Filter the data to find rows where new cases or new deaths are larger than 0.


### Datasets

- **Our World in Data**: Global COVID-19 data, which includes various metrics such as total cases, deaths, and testing numbers.
- **Johns Hopkins University CSSE**: Time series data for global confirmed COVID-19 cases and deaths.

### Notes

- The datasets are loaded directly from online sources, so an active internet connection is required.
- This lab is designed for educational purposes, focusing on data exploration and cleaning techniques.

### License

This project is licensed under the MIT License.

