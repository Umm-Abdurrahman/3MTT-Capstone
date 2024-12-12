# 3MTT-Capstone
# COVID-19 Dataset Analysis

This repository contains a Jupyter Notebook for performing exploratory data analysis (EDA) on a COVID-19 dataset. The analysis provides insights into global death trends and distributions based on the World Health Organization (WHO) regions and other relevant features.

# Features

The project includes:

# Data Preprocessing:

Loading the dataset using Pandas.

Inspecting the dataset for null values and duplicates.

Cleaning and transforming the data, including:

Dropping unnecessary columns.

Handling missing values in Province/State.

Standardizing the Deaths column for further analysis.

# Exploratory Data Analysis (EDA):

Summary statistics of the dataset.

Boxplot visualization for Deaths to detect outliers.

Grouping data by WHO regions and countries for comparative analysis.

Visualization of deaths by region using pie charts.

Time-based analysis by adding Year and Month columns to the dataset.

# Visualizations:

Pie charts showing the percentage distribution of deaths across WHO regions and specific countries.

Bar charts depicting the monthly total deaths globally.

# Prerequisites

To run the notebook, ensure you have the following Python libraries installed:

# NumPy

# pandas

# matplotlib

# seaborn

# scikit-learn

You can install them using pip:

pip install numpy pandas matplotlib seaborn scikit-learn

# Usage

Clone this repository:

git clone https://github.com/Ummm-Abdurrahman/3MTT-Capstone/covid19-analysis.git

Navigate to the project directory and open the notebook:

jupyter notebook covid-19-dataset-analysis.ipynb

Run the cells sequentially to reproduce the analysis.

# Dataset

The dataset used for this analysis is a cleaned version of COVID-19 global data. It includes columns such as:

Date: The date of record.

Country/Region: The country or region of the record.

Province/State: The province or state (if applicable).

WHO Region: The corresponding WHO region.

Deaths: Total deaths reported.

The dataset is saved at the appropriate file path specified in the notebook.

# Results

The analysis provides the following insights:

A regional distribution of deaths by WHO regions.

Top 5 countries with the highest death counts in specific WHO regions.

Monthly trends in COVID-19 deaths.

# License

This project is licensed under the MIT License. See the LICENSE file for details.

# Acknowledgments

The dataset used is sourced from Kaggle.

# Contact

If you have any questions or feedback, feel free to contact the repository owner


