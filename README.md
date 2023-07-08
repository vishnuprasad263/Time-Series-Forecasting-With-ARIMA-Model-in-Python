# Time Series Forecasting With ARIMA Model in Python for Temperature Prediction

This repository provides an implementation of time series forecasting using the ARIMA model in Python. The goal is to predict temperature values based on historical data. The ARIMA (AutoRegressive Integrated Moving Average) model is a popular technique for time series forecasting that can capture both autoregressive (AR) and moving average (MA) behavior in the data.

## Prerequisites

To run the code in this repository, you need to have the following dependencies installed:

- Python (version 3.6 or later)
- NumPy
- pandas
- statsmodels

You can install the required packages by running the following command:

```
pip install numpy pandas statsmodels
```

## Usage

1. Clone the repository to your local machine or download the source code.

```
git clone https://github.com/your-username/time-series-forecasting.git
```

2. Navigate to the project directory.

```
cd time-series-forecasting
```

3. Prepare your temperature data in a CSV file. The file should have two columns: "Date" and "Temperature". Make sure the dates are in a proper date format and the temperatures are numeric.

4. Modify the `forecast.py` file to specify the path to your input data file.

```python
# Specify the path to the input data file
data_file = 'path/to/your/data.csv'
```

5. Run the `forecast.py` script to perform the temperature prediction.

```
python forecast.py
```

6. The script will fit an ARIMA model to the historical temperature data and generate forecasts for future time periods. The predicted temperature values will be saved in a file named `predictions.csv` in the project directory.

## Customization

The ARIMA model can be customized based on your specific requirements. You can modify the following parameters in the `forecast.py` file:

- `p`: The order of the autoregressive component.
- `d`: The degree of differencing.
- `q`: The order of the moving average component.

You can experiment with different values for these parameters to improve the forecast accuracy.

## Contributing

If you find any issues or have suggestions for improvement, please feel free to contribute! You can submit a pull request or open an issue on the repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

This implementation is based on the concepts and techniques presented in time series forecasting literature and the `statsmodels` library documentation.
