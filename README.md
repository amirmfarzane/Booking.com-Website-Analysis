# Booking.com Website Analysis

## Overview

This project involves a comprehensive analysis of Booking.com data, undertaken as part of a Data Science course at the University of Tehran. The project includes data scraping, feature engineering, exploratory data analysis (EDA), and model training to gain insights and predictive capabilities pertinent to the hospitality and travel industry.

## Table of Contents

1. [Project Structure](#project-structure)
2. [Data Scraping](#data-scraping)
3. [Feature Engineering](#feature-engineering)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Model Training](#model-training)
6. [Results](#results)
7. [Conclusion](#conclusion)
8. [Installation](#installation)
9. [Usage](#usage)
10. [Contributors](#contributors)
11. [License](#license)

## Project Structure


## Data Scraping

Data was scraped from Booking.com using custom Python scripts. The scraping process involved:

- Extracting information on hotels, such as prices, ratings, location, amenities, and reviews.
- Ensuring data quality and handling issues like missing values and duplicates.

For more details, refer to the notebook: `notebooks/01_data_scraping.ipynb`

## Feature Engineering

The feature engineering process transformed the raw data into a suitable format for analysis and modeling. Key steps included:

- Creating new features from the raw data.
- Normalizing and encoding categorical variables.
- Handling missing values and outliers.

For more details, refer to the notebook: `notebooks/02_feature_engineering.ipynb`

## Exploratory Data Analysis (EDA)

EDA was performed to uncover patterns, trends, and relationships in the data. Key analyses included:

- Descriptive statistics and data distributions.
- Correlation analysis and feature importance.
- Visualizations to aid understanding of the data.

For more details, refer to the notebook: `notebooks/03_eda.ipynb`

## Model Training

Several machine learning models were trained to predict hotel prices and ratings based on the engineered features. The process involved:

- Splitting the data into training and testing sets.
- Training multiple models and tuning hyperparameters.
- Evaluating model performance using appropriate metrics.

For more details, refer to the notebook: `notebooks/04_model_training.ipynb`

## Results

The results of the analysis include:

- Insights gained from the EDA.
- Performance metrics of the trained models.
- Visualizations and summaries of the findings.

## Conclusion

This project successfully demonstrated the application of data science techniques to Booking.com data. The insights and predictive models developed can be valuable for stakeholders in the hospitality and travel industry.

## Installation

To install the required dependencies, run:

```bash
pip install -r requirements.txt
