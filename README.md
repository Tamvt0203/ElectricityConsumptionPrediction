# Electricity Consumption Prediction

## Project Overview

The **Electricity Consumption Prediction** project aims to develop a predictive model for forecasting electricity usage based on historical data. Accurate electricity consumption predictions are essential for energy providers, utility companies, and consumers to manage and optimize energy resources efficiently.

## Features

- **Data Preprocessing**: Handling missing data, feature scaling, and other preprocessing steps.
- **Feature Engineering**: Identifying key features that influence electricity consumption.
- **Modeling**: Implementing various machine learning algorithms to predict future electricity consumption.
- **Evaluation**: Assessing model performance using metrics such as MAE, RMSE, and R².

## Datasets

- **Training Data**: Historical electricity consumption data (`train.csv`), which includes features such as temperature, humidity, day of the week, and other relevant factors.
- **Testing Data**: A separate dataset (`test.csv`) used to evaluate the performance of the predictive model.

### Target Variable

- `new_total_usage`: This column in the dataset represents the total electricity consumption, which the model aims to predict.

## Requirements

To run this project, you need to install the dependencies listed in the `environment.yml` file. You can create the conda environment using:

```bash
conda env create -f environment.yml
