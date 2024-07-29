# Booking.com Website Analysis

## Overview

This project involves a comprehensive analysis of Booking.com data, undertaken as part of a Data Science course at the University of Tehran. The project includes data scraping, feature engineering, exploratory data analysis (EDA), and model training to gain insights and predictive capabilities pertinent to the hospitality and travel industry.

## Table of Contents

1. [Project Structure](#project-structure)
2. [Data Scraping](#data-scraping)
3. [Feature Engineering and EDA](#feature-engineering)
4. [Model Training](#model-training)
5. [Results](#results)
6. [Conclusion](#conclusion)
7. [Usage](#usage)
8. [Contributors](#contributors)
9. [License](#license)

## Project Structure


## Data Scraping

Data was scraped from Booking.com using custom Python scripts and beautiful soup. The scraping process involved:

- Extracting information on hotels, such as prices, ratings, location, amenities, and reviews.
- Choosing number of adults and number of nights is possible to change based on ypur need.
- Also is possible to choose diffrent cities but we extracted city key from html script of website and be used.

For more details of this phase description, refer to the notebook: `P0/DS-Project-P0.pdf`
For more details of this phase implementation, refer to the notebook: `scrap.ipynb`

## Feature Engineering and EDA

The feature engineering process transformed the raw data into a suitable format for analysis and modeling. Key steps included:

- Creating new features from the raw data.
- Normalizing and encoding categorical variables.
- Handling missing values and outliers.

EDA was performed to uncover patterns, trends, and relationships in the data. Key analyses included:

- Descriptive statistics and data distributions.
- Correlation analysis and feature importance.
- Visualizations to aid understanding of the data.
- 

For more details of this phase description, refer to the notebook: `P1/DS-Project-P1.pdf`
For more details of this phase implementation, refer to the notebook: `P1/DS-Project-P1.ipynb`

## Model training to price prediction and using another AI methods.

Several machine learning models were trained to predict hotel prices based on the engineered features. The process involved:

- Splitting the data into training and testing sets.
- Training multiple models and tuning hyperparameters.
- Evaluating model performance using appropriate metrics.

For more details of this phase description, refer to the notebook: `P2/DS-Project-P2.pdf`
For more details of this phase implementation, refer to the notebook: `P2/DS-Project-P2.ipynb`

## Results

The results of the analysis include:

- Insights gained from the EDA.
- Performance metrics of the trained models.
- Visualizations and summaries of the findings.

- Finall results on test data
  Model                    Accuracy
---------------------  ----------
XGboot                       0.98
Forest regression            0.94
Nural network                0.9
KNN                          0.84
Polynomial regression        0.79
MLP regression               0.77
Linear regression            0.57

## Conclusion

This project successfully demonstrated the application of data science techniques to Booking.com data. The insights and predictive models developed can be valuable for stakeholders in the hospitality and travel industry.
