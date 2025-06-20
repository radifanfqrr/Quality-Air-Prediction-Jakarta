# Quality-Air-Prediction-Jakarta

## Overview
This project aims to predict the air quality in Jakarta by analyzing air pollutant concentrations like **PM10**, **SO2**, **CO**, **O3**, and **NO2**. Using **Random Forest** for classification and regression, the model predicts the concentration of **PM10** and the quality category of the air.

The project utilizes machine learning techniques, specifically **Random Forest**, to create predictive models based on air quality data from various monitoring stations across Jakarta.

## Objectives
- **Data Exploration**: Analyze the distribution of air quality features and detect any outliers.
- **Data Cleaning**: Handle missing values and prepare the dataset for modeling.
- **Feature Engineering**: Create meaningful features from the data to improve the model’s predictive power.
- **Model Training**: Train a **Random Forest** model to predict **PM10** concentration and air quality categories.
- **Model Evaluation**: Evaluate model performance using metrics such as accuracy, precision, recall, and confusion matrix.
- **Future Predictions**: Use the trained model to project air quality for the next 5 years.

## Dataset
The dataset contains the following columns:
- **pm10**: Concentration of PM10 (particulate matter).
- **so2**: Concentration of sulfur dioxide.
- **co**: Concentration of carbon monoxide.
- **o3**: Concentration of ozone.
- **no2**: Concentration of nitrogen dioxide.
- **max**: Maximum concentration of pollutants.
- **stasiun**: The monitoring station.
- **tanggal**: The date of data collection.
- **categori**: The air quality category.

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Installation
Clone the repository and install the required libraries:
```bash
git clone https://github.com/yourusername/Quality-Air-Prediction-Jakarta.git
cd Quality-Air-Prediction-Jakarta
pip install -r requirements.txt
