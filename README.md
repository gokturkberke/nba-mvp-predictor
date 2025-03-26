# NBA MVP Prediction

This project aims to predict the NBA MVP (Most Valuable Player) award winner using machine learning techniques. By analyzing player statistics from the 1993 to 2023 NBA seasons, the model attempts to predict MVP rankings based on historical data.

## Project Overview

The project includes the following steps:

### 1. Web Scraping
Data is gathered from various sources to build a dataset of player statistics.

### 2. Data Cleaning
The dataset is cleaned by handling missing values and performing necessary transformations.

### 3. Feature Selection
Key predictors such as player age, games played, field goals, points, and other performance metrics are selected for model training.

### 4. Model Training
A linear regression model is trained to predict the MVP ranking based on selected features.

### 5. Backtesting
The model is validated by comparing predictions with actual historical MVP rankings for each season.

## Installation

To run this project, you need to install the required dependencies.
pip install -r requirements.txt
python mvp_prediction.py

