# Unicorn Companies Missing Data EDA

## Project Overview

This project focuses on addressing missing data in a dataset of unicorn companies—companies valued at over one billion dollars. By effectively managing missing values, we aim to produce a clean and useful dataset that provides insights into potential business opportunities for investors.

The analysis includes filtering unicorn companies by industry and location, generating country-specific valuations, and visualizing the results through maps and charts.

## Table of Contents

- [Introduction](#introduction)
- [Tools Used](#tools-used)
- [Project Structure](#project-structure)
- [EDA Steps](#eda-steps)
  - [Step 1: Imports](#step-1-imports)
  - [Step 2: Data Exploration](#step-2-data-exploration)
  - [Step 3: Handling Missing Values](#step-3-handling-missing-values)
  - [Step 4: Results and Evaluation](#step-4-results-and-evaluation)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)
- [References](#references)

## Introduction

In the world of finance, unicorn companies represent significant investment opportunities. This project analyzes a dataset containing 1074 unicorn companies to address missing data, explore trends, and identify potential investment opportunities for an investor.

The analysis aims to answer key questions:

- Which unicorn companies are in the hardware and AI industries located in specific cities?
- What are the top countries by total company valuation, excluding major markets?
- How can we visualize global valuations and trends in unicorn company presence?

## Tools Used

- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.
- **Matplotlib**: For visualizations.
- **Plotly**: For interactive plots.
- **Seaborn**: For advanced visualizations.

## Project Structure

This Jupyter notebook is divided into the following sections:

- **Step 1: Imports**: Import relevant libraries.
- **Step 2: Data Exploration**: Explore dataset characteristics (e.g., structure, types, and uniqueness).
- **Step 3: Handling Missing Values**: Analyze and address missing data in the dataset.
- **Step 4: Results and Evaluation**: Visualize findings and present insights.

## EDA Steps

### Step 1: Imports
Import the necessary libraries, including Pandas, NumPy, Matplotlib, Plotly, and Seaborn.

### Step 2: Data Exploration
Explore the dataset by:
- Displaying the first 10 rows to understand the structure.
- Identifying the number of rows and columns.
- Checking for duplicates and null values.
- Analyzing data types and statistical properties.

### Step 3: Handling Missing Values
- Investigate missing values and their context.
- Evaluate methods to address missing data, including removing rows/columns and imputation.
- Decide the most effective approach based on the data context.

### Step 4: Results and Evaluation
- Filter unicorn companies by industry and location to meet investor criteria.
- Calculate and visualize country-specific valuations, excluding major outlier countries.
- Create maps to visualize global valuations and trends.

## Key Insights

- Eight companies meet the investor's criteria in the hardware and AI industries.
- The analysis highlights the top countries by unicorn company valuations while excluding major markets.
- Visualizations effectively illustrate the distribution of unicorn companies and their valuations across various regions.

## Conclusion

This project provides a comprehensive analysis of unicorn companies, addressing missing data and delivering valuable insights into potential investment opportunities. The findings can guide investors in identifying promising markets and industries.

## How to Run

1. **Clone the repository**:

    ```bash
    git clone <https://github.com/MahmoudKhaled98/Unicorn-Companies-Missing-Data-EDA.git>
    ```

2. **Install the required dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter notebook**:

    ```bash
    jupyter notebook
    ```

## References

- [Bhat, M.A. *Unicorn Companies*](https://www.kaggle.com/datasets/mysarahmadbhat/unicorn-companies)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Plotly Documentation](https://plotly.com/python/)
