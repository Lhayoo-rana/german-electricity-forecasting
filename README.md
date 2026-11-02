# Germany Electricity Consumption Forecasting

## Project Overview

This project focuses on analysing and forecasting electricity consumption in Germany using historical electricity data. The aim is to apply data science and machine learning techniques to identify electricity consumption patterns and develop forecasting models that can estimate future electricity demand.

Accurate electricity demand forecasting can support energy planning, resource allocation, grid management, and decision-making in the energy sector.

## Research Problem

Electricity consumption changes over time due to factors such as weather conditions, seasonal patterns, economic activity, and human behaviour. Understanding these patterns and predicting future demand is important for maintaining a reliable and efficient electricity supply.

This project investigates how historical electricity consumption data can be used to forecast future demand in Germany.

## Project Objectives

- Collect and understand historical electricity consumption data.
- Clean and preprocess the dataset.
- Explore daily, weekly, and seasonal consumption patterns.
- Identify important trends and variations in electricity demand.
- Develop and evaluate machine learning forecasting models.
- Compare model performance and identify a suitable forecasting approach.

## Dataset

**Source:** SMARD – German electricity market data platform  
**Website:** https://www.smard.de/en/downloadcenter  
**Geographical coverage:** Germany  
**Data period:** 1 January 2024 – 31 December 2025  
**Data frequency:** Hourly  
**Main target variable:** Grid load (MWh)

The dataset contains electricity-related variables, including grid load, grid load including hydro pumped storage, hydro pumped storage, and residual load.

**Data licence:** Creative Commons Attribution 4.0 International (CC BY 4.0), subject to the applicable SMARD data-use terms. Attribution will be provided when using the data.

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

1. Data collection
2. Data cleaning and preprocessing
3. Exploratory data analysis (EDA)
4. Feature engineering
5. Model development
6. Model evaluation
7. Results and conclusions

## Planned Machine Learning Models

- Linear Regression
- Random Forest Regressor
- Additional time-series forecasting approaches, depending on the results of exploratory analysis.

## Repository Structure

```text
germany-electricity-forecasting/
│
├── data/
├── figures/
├── notebooks/
├── reports/
├── src/
├── README.md
└── requirements.txt
```

## Project Status

**Current stage:** Project setup and dataset preparation.

Further updates will be added as data analysis, model development, and evaluation progress.

## Data Attribution

Electricity data sourced from SMARD, the German electricity market data platform. Please refer to the SMARD data-use terms: https://www.smard.de/en/all-about-our-data-download-section-210130
