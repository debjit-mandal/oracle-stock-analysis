# Oracle Stock Price Analysis

This project provides a comprehensive analysis of Oracle's stock price dataset. The dataset includes historical stock prices since Oracle's IPO in 1986 and contains essential columns such as date, opening price, highest price of the day, lowest price of the day, closing price, adjusted closing price, and trading volume. 

The analysis includes:
- Data Preprocessing
- Descriptive Statistics
- Visualizations
- Time Series Analysis
- Predictive Modeling
- Volatility Analysis
- Volume Analysis
- Insights and Conclusions

## Dataset

The dataset used in this project can be found in Kaggle: [Oracle Stock Price Dataset 💻☁️🔍](https://www.kaggle.com/datasets/mayankanand2701/oracle-stock-price-dataset). It includes the following columns:
- **Date**: The date of the stock price data.
- **Open**: The opening price of the stock on that day.
- **High**: The highest price of the stock on that day.
- **Low**: The lowest price of the stock on that day.
- **Close**: The closing price of the stock on that day.
- **Adj Close**: The adjusted closing price of the stock, accounting for any corporate actions such as stock splits or dividends.
- **Volume**: The trading volume, i.e., the number of shares traded on that day.

## Analysis Overview

### Data Preprocessing
- Converted the 'Date' column to datetime format.
- Set the 'Date' column as the index.
- Checked for missing values.

### Descriptive Statistics
- Calculated summary statistics of the dataset.

### Visualizations
- Plotted the closing prices over time.
- Plotted the trading volumes over time.

### Time Series Analysis
- Decomposed the time series to understand the components such as trend, seasonality, and noise.
- Calculated and plotted rolling mean and standard deviation.
- Performed the Augmented Dickey-Fuller test to check for stationarity.
- Plotted autocorrelation and partial autocorrelation functions.

### Predictive Modeling
- Built and evaluated an ARIMA model for forecasting future stock prices.
- Built and evaluated a GARCH model for forecasting stock price volatility.
- Built and evaluated a Linear Regression model for predicting stock prices based on date features.

### Volatility Analysis
- Analyzed daily returns and their volatility.

### Volume Analysis
- Analyzed the relationship between trading volume and stock prices.

### Insights and Conclusions
- Summarized key findings and insights from the analyses.

## Results

### ARIMA Model
- Provided reasonable forecasts, capturing the general direction of stock price movements.

### GARCH Model
- Effectively captured the volatility in stock returns, highlighting periods of higher and lower volatility.

### Linear Regression Model
- Provided a baseline prediction of stock prices based on date features.

### Volatility and Volume Analysis
- Showed significant volatility in daily returns.
- Indicated a positive relationship between trading volume and stock prices.

## Conclusion

This analysis provides a comprehensive understanding of Oracle's stock price behavior over time, highlighting trends, volatility, and potential predictive modeling approaches. The insights can aid investors and analysts in making informed decisions based on historical data and forecasts.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python Libraries: pandas, numpy, matplotlib, seaborn, statsmodels, arch, sklearn

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/debjit-mandal/oracle-stock-analysis.git
    ```
2. Navigate to the project directory:
    ```sh
    cd oracle-stock-analysis
    ```
3. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

### Usage
1. Open the Jupyter Notebook:
    ```sh
    jupyter notebook Oracle_Stock_Analysis.ipynb
    ```
2. Run the cells in the notebook to perform the analysis.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
