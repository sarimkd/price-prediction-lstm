 # Stock Price Prediction using LSTM Neural Networks
This project demonstrates how to predict stock prices using Long Short-Term Memory (LSTM) neural networks. LSTM networks are a type of recurrent neural network (RNN) that are well-suited for sequence data, making them popular for time series forecasting tasks like stock price prediction. Amazon and Google are the two companies used for this project.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Notebooks](#notebooks)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Predicting stock prices is a challenging task due to the complex and volatile nature of financial markets. This project explores the use of LSTM neural networks to predict stock prices based on historical price data and technical indicators.

## Installation
1. Clone this repository:
```
git clone https://github.com/sarimkd/price-prediction-lstm.git
```
2. Navigate to the project folder:
```
cd price-prediction-lstm
```
3. Create a virtual environment (optional but recommended):
```
python -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate
```
4. Install the required packages:
```
pip install -r requirements.txt
```

## Usage
1. Launch Jupyter Notebook:
```
jupyter notebook
```
2. Open the relevant notebook to explore the code and predictions.
3. Follow the notebook's instructions to load data, preprocess it, build and train LSTM models, and make predictions.

## Data
The project uses historical stock price data from [Yahoo Finance](https://finance.yahoo.com/) for training and testing the LSTM models. You can use any publicly available financial data source or a dataset of your choice.

## Notebooks
- `amazon_predict_stock.ipynb`: The notebook that contains the step-by-step process of loading data, preprocessing, building LSTM models, training, and making predictions with Amazon Data.
- `google_predict_stock.ipynb`: The notebook that contains the step-by-step process of loading data, preprocessing, building LSTM models, training, and making predictions with Google Data.

## Results
The performance of the LSTM models is evaluated using various metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) score. The notebook visualizes the predicted vs. actual stock price trends.

## Contributing
Contributions are welcome! If you find any issues or want to enhance the project, feel free to submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).