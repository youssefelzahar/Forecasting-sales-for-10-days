# Forecasting Sales for 10 Days

This repository contains the implementation of a **Sales Forecasting Model** designed to predict sales for the next 10 days. The project combines data preprocessing, feature engineering, and advanced machine learning algorithms to generate accurate forecasts.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Forecasting Techniques](#forecasting-techniques)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The goal of this project is to:

1. Forecast sales for the next 10 days at a granular level (e.g., product and city).
2. Enhance forecasting accuracy using advanced machine learning techniques.
3. Provide a reproducible pipeline for sales forecasting tasks.

## Features

- **Preprocessing pipeline**:
  - Handling missing data.
  - Scaling features with MinMaxScaler.
  - Generating lag features and rolling averages.
- **Forecasting algorithms**:
  - ARIMA/SARIMA for time-series analysis.
  - XGBoost for machine learning-based forecasting.
- **Evaluation metrics**:
  - Mean Squared Error (MSE).
  - Mean Absolute Error (MAE).
  - R-squared score.
- **Future date generation** with specific hour components.

## Dataset

The dataset used for this project contains:

- Sales data for multiple products and cities.
- Features such as discount, unit price, and sales quantity.

**Note:** The dataset is not included in this repository. Use publicly available datasets or your dataset for training and testing.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/youssefelzahar/Forecasting-sales-for-10-days.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Forecasting-sales-for-10-days
   ```

3. Launch the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook
   ```

## Usage

1. Load the dataset and preprocess it using the provided scripts.
2. Configure hyperparameters for the forecasting model.
3. Train the model and evaluate its performance.
4. Generate future sales predictions for the next 10 days.

## Forecasting Techniques

The project explores the following techniques:

1. **Time-Series Models:**
   - ARIMA/SARIMA for univariate sales data.

2. **Machine Learning Models:**
   - **XGBoost:** Incorporates additional features like lag values, rolling averages, and categorical encodings for enhanced performance.

## Results

- **Evaluation Metrics:**
  - Mean Squared Error: `1.8801850638529196`
  - Mean Absolute Error: `1.085411894511039`
  - R-squared: `0.3096357583999634`

- **Best Model:**
  The **XGBoost Model** achieved the best performance due to its ability to leverage feature engineering effectively.

Detailed results and visualizations are available in the project notebook.

## Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
