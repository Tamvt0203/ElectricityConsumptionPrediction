# Electricity Consumption Prediction

## Project Overview

The **Electricity Consumption Prediction** project aims to develop a predictive model for forecasting electricity usage based on historical data. Accurate electricity consumption predictions are essential for energy providers, utility companies, and consumers to manage and optimize energy resources efficiently.

## Features

- **Data Preprocessing**: Includes several steps such as data crawling, cleaning, filling missing values, and visualizing feature distributions.
- **Feature Engineering**: Identifying key features that influence electricity consumption, such as temperature, holidays, day of the week, etc.
- **Modeling**: Implementing various machine learning algorithms to predict future electricity consumption, includes: RandomForest, DecisionTree, LinearRegression, Prophet and LSTM.
- **Evaluation**: Assessing model performance using metrics such as MAE, MSE, RMSE, and MAPE.

## Datasets

- **Training Data**: Historical electricity consumption data (`train.csv`), which includes features , such as temperature, holidays, day of the week, etc.
- **Testing Data**: A separate dataset (`test.csv`) used to evaluate the performance of the predictive model.

### Target Variable

- `new_total_usage`: This column in the dataset represents the total electricity consumption, which the model aims to predict.

## Requirements

To run this project, you need to install the dependencies listed in the `environment.yml` file. You can create the conda environment using:

```bash
conda env create -f environment.yml

