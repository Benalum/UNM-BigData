[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/42-BwFfC)
[![Work in MakeCode](https://classroom.github.com/assets/work-in-make-code-8824cc13a1a3f34ffcd245c82f0ae96fdae6b7d554b6539aec3a03a70825519c.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15834324&assignment_repo_type=AssignmentRepo)
# Lab Data Visualization and Exploratory Data Analysis (EDA)

This lab focuses on data visualization and exploratory data analysis (EDA) of COVID-19 data using Python libraries such as Pandas, Matplotlib, Seaborn, and Plotly. The main goal is to derive insights from visualizing the global and country-level trends of COVID-19 cases, deaths, and vaccination progress.

## Prerequisites

Before running the code, make sure you have the following Python libraries installed:

- `pandas`
- `matplotlib`
- `seaborn`
- `plotly`

You can install the required libraries using pip:

```bash
pip install pandas matplotlib seaborn plotly
```

## Data Source

The code uses the COVID-19 dataset from "Our World in Data" available at: [Our World in Data - COVID-19 Dataset](https://covid.ourworldindata.org/data/owid-covid-data.csv)

## Content

### Data Loading and Cleaning

- Load the COVID-19 dataset using Pandas.
- Check for missing values and handle them by dropping rows with missing values in specific columns.

### VIsualization of Global Trends

- Plot the total number of cases and deaths cumulatively over time globally.
- Use both linear and logarithmic scales for better insight into trends.

### Country-Level Analysis

- Identify the country with the maximum and minimum total cases.
- Plot the daily new cases and deaths for these countries.
- Compare and contrast linear and logarithmic scales for better understanding.

### Analysis of Selected Countries

- Visualize the number of daily new cases and deaths for selected countries (United States, India, Brazil, Germany, Mexico, Australia).
- Compare these trends across countries.

### 5. Vaccination Progress

- Plot the total confirmed cases and vaccination progress over time for selected countries.

### Correlation and Relationship Analysis

- Use Seaborn to create scatter plots and pair plots to visualize the relationship between different COVID-19 metrics such as total cases, total deaths, GDP per capita, and life expectancy.

### Case Fatality Rate Analysis

- Calculate the Case Fatality Rate (CFR) for each country and visualize the countries with the highest CFRs.

### Global and Country-Level Distribution Analysis

- Visualize the distribution of cases and deaths per million people for different countries using bar plots and histograms.
- Create a choropleth map to visualize the total COVID-19 cases per country using Plotly.

### Other Visualizations

- Generate 3D scatter plots and box plots to explore more advanced relationships between variables, such as total cases per million, GDP per capita, and life expectancy.

## Questions

After generating the plots, you can derive insights into the spread and impact of COVID-19 globally and within countries. Some key questions to consider:

- What patterns emerge from daily new cases and deaths?
- How do different countries compare in terms of COVID-19 cases and vaccination progress?
- What are the advantages and disadvantages of using linear vs. logarithmic scales in visualizations?
- How does GDP per capita relate to the number of cases per million in different continents?



## Acknowledgments

- [Our World in Data](https://ourworldindata.org/) for providing the COVID-19 dataset.
