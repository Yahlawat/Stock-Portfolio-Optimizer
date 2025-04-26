# Stock Portfolio Optimizer

This project builds an optimized stock portfolio by combining financial data analysis with machine learning techniques.  

I have selected major stocks across sectors, reduced dimensions with t-SNE, grouped similar stocks using K-Means clustering, and applied constrained optimization to maximize Sharpe and Sortino ratios while maintaining diversification.

# <img src="./Images/project_image.png" alt="" width="300">

## Features

- Fetch historical stock data (`yfinance`)
- Calculate returns, volatility, Sharpe and Sortino ratios
- Apply t-SNE and K-Means clustering to group similar stocks
- Optimize portfolios with diversification and allocation constraints
- Simulate 10,000 portfolios using Monte Carlo methods
- Visualize efficient frontier and compare portfolio strategies

## Project Structure

```
portfolio-optimizer/
├── portfolio_optimizer.ipynb    # Main Jupyter notebook
├── requirements.txt             # Python package dependencies
└── README.md                    # Project documentation
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
