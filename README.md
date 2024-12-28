# Seattle Weather Analysis and Prediction 🌦️

This project focuses on analyzing and predicting weather patterns in Seattle using machine learning techniques. The goal is to provide accurate weather forecasts based on historical data.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Results](#results)
- [Contributing](#contributing)

## Project Overview
The goal of this project is to analyze Seattle's weather data and build predictive models to forecast weather conditions. The project utilizes various machine learning algorithms to predict whether it will rain based on historical weather data.

## Dataset
The dataset used in this project is `seattle-weather.csv`, which contains daily weather observations from Seattle. The key features include:
- Date
- Precipitation
- Maximum and Minimum Temperature
- Wind
- Weather Condition

## Installation
To run this project, you need to have Python installed along with the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- joblib

You can install the required libraries using pip:
## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/adilmrcodeaz/seattle-weather-analysis.git
   cd seattle-weather-analysis
   ```

2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```

3. Follow the steps in the notebook to perform data analysis and train the models.

## Features
- Data Preprocessing: Clean and prepare weather data for analysis.
-Feature Engineering: Create meaningful features like temperature range, average, and seasonal indicators.
-Machine Learning Model: Train a Random Forest Classifier to predict weather conditions.
-Visualization: Use Power BI for interactive data visualization.
-Performance Evaluation: Assess model accuracy and feature importance.

## Model Details
- Algorithm: Random Forest Classifier
- Features: Temperature, precipitation, wind speed, seasonal indicators, previous day's conditions
- Performance: Achieves approximately 85-90% accuracy

## Results
The best performing model was the Random Forest classifier with the following metrics:
- Accuracy: 88%
- Precision: 87%
- Recall: 86%
- F1 Score: 86%
- AUC-ROC: 0.90

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

---
