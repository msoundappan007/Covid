# Exploratory Data Analysis (EDA) using COVID Dataset

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a COVID dataset to uncover trends, patterns, and insights related to the COVID-19 pandemic. EDA is an essential process in data analysis, used to understand the dataset's structure and characteristics through statistical summaries and visualizations.

## Dataset

The dataset used for this project contains various metrics related to COVID-19, such as case counts, vaccination rates, and other relevant health data. The dataset can be found in the `data/` directory as `covid_data.csv`.

## Features

- **Data Cleaning**: Handle missing values, outliers, and inconsistencies in the dataset.
- **Statistical Summaries**: Compute descriptive statistics to summarize the dataset's main characteristics.
- **Data Visualization**: Create visualizations such as histograms, bar charts, line plots, and heatmaps to illustrate trends and patterns.
- **Trend Analysis**: Analyze temporal and geographical trends related to COVID-19.
- **Correlation Analysis**: Explore relationships between different variables in the dataset.

## Installation and Setup

1. **Clone the repository**:
    ```sh
    git clone https://github.com/msoundappan007/eda-covid-dataset.git
    cd eda-covid-dataset
    ```

2. **Create and activate a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```



## Usage

1. **Load the Dataset**:
   - The dataset can be loaded using Python libraries such as Pandas. Use the script `eda.py` to load and preprocess the data.
   
2. **Perform EDA**:
   - Run the `eda.py` script to perform data cleaning, compute statistical summaries, and generate visualizations.
    ```sh
    python eda.py
    ```

3. **Explore Results**:
   - Review the output and visualizations saved in the `results/` directory.
   - Analyze trends, patterns, and correlations revealed by the EDA process.

## Results

- **Data Cleaning**: Details of how missing values and outliers were handled.
- **Statistical Summaries**: Descriptive statistics for the dataset.
- **Visualizations**: Graphical representations of trends, distributions, and correlations.
- **Insights**: Key findings and patterns discovered during the analysis.

