# Wine-Quality-Prediction

## Project Overview

This project aims to predict the quality of wine based on its chemical properties. The model uses a dataset of red and white wines with various properties such as acidity, alcohol content, and pH, along with a quality rating from 0 to 10.

## Dataset

The dataset used in this project is the Wine Quality dataset, which is available on the UCI Machine Learning Repository. The dataset contains various properties of red and white wines, along with a quality rating from 0 to 10.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries (pandas, numpy, scikit-learn, matplotlib, seaborn)

### Installation

1. Clone the repository: git clone https://github.com/your_username/wine-quality-prediction.git

2. Install the required libraries: pip install pip install pandas numpy scikit-learn matplotlib seaborn joblib


### Usage

1. Open the Jupyter Notebook `wine_quality_prediction.ipynb`.
2. Run the cells to train the model and make predictions.

## Model

The model used in this project is a Random Forest regressor, which is trained on the training data and evaluated on the testing data. The model's performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Results

The model achieved a Mean Squared Error (MSE) of 0.3046 on the testing data, indicating a good fit to the data. The best parameters for the Random Forest regressor were:

- max_depth: 30
- min_samples_leaf: 1
- min_samples_split: 2
- n_estimators: 150
