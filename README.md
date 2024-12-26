# Seattle Weather Analysis and Prediction

This project involves analyzing and predicting weather patterns in Seattle using a dataset of historical weather data. The project includes data cleaning, feature engineering, exploratory data analysis, and machine learning model training.

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
   git clone https://github.com/yourusername/seattle-weather-analysis.git
   cd seattle-weather-analysis
   ```

2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```

3. Follow the steps in the notebook to perform data analysis and train the models.

## Features
- **Data Cleaning**: Handling missing values, duplicates, and outliers.
- **Feature Engineering**: Creating new features like temperature range and season.
- **Exploratory Data Analysis**: Visualizing data trends and distributions.
- **Machine Learning Models**: Training and evaluating models like Random Forest, Gradient Boosting, and SVM.
- **Model Evaluation**: Using metrics like accuracy, precision, recall, and F1 score.

## Results
The best performing model was the Random Forest classifier with the following metrics:
- Accuracy: 0.95
- Precision: 0.94
- Recall: 0.93
- F1 Score: 0.93

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

---
