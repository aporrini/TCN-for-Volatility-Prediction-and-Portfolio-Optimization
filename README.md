
# TCN for Volatility Prediction and Portfolio Optimization

## Description

This project implements a Temporal Convolutional Network (TCN) to forecast the volatility of S&P 500 sector ETFs. The predicted volatility is then used to construct a dynamic portfolio with the goal of reducing realized volatility compared to the SPY benchmark. Macroeconomic variables are included to improve the accuracy of the forecasts.

## System Requirements

- Python 3.8 or higher

### Required Python Packages

- numpy  
- pandas  
- torch  
- matplotlib  
- scikit-learn  

To install all dependencies, run:

```bash
pip install -r requirements.txt
```

## Usage

1. Prepare the data:  
   Make sure the following files are available in the `/data` folder:
   - `final_dataset_daily.csv`
   - `macroeconomic_inputs.csv` (if applicable)

2. Run the TCN model and Run the portfolio optimization:  
   Execute the notebook

## Expected Results

- A dynamically rebalanced portfolio using the predicted volatility matrix
- Lower realized volatility than SPY
- Output plots for cumulative return, portfolio composition, and volatility metrics

## Contributions

For issues, suggestions, or improvements, feel free to open an issue or pull request in the GitHub repository.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
