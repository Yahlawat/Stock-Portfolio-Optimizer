# Stock Portfolio Optimizer

A comprehensive Python-based portfolio optimization tool that implements Modern Portfolio Theory (MPT), Mean-Variance Optimization (MVO), and Monte Carlo simulations to find optimal asset allocations. The tool includes advanced features like cluster-based constraints, sector analysis, and multiple optimization objectives.

## Features

- Historical stock data retrieval and analysis
- Portfolio optimization with Efficient Frontier and Monte Carlo simulations
- Risk and return calculations with multiple metrics (Sharpe, Sortino)
- Custom constraints including cluster-based (max 40% per cluster)
- Sector analysis and exposure tracking
- Interactive visualizations
- Stock clustering using K-means
- Comprehensive performance metrics (returns, volatility, ratios)

## Prerequisites

- Python 3.8 or higher
- pip

## Setup Instructions

1. Clone the repository (optional):
```bash
git clone <repository-url>
cd portfolio-optimizer
```

2. Create a Python virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

5. Open the `portfolio_optimizer.ipynb` notebook to start using the tool.

## Project Structure

```
portfolio-optimizer/
├── portfolio_optimizer.ipynb    # Main Jupyter notebook
├── requirements.txt             # Python package dependencies
└── README.md                    # Project documentation
```

## Usage Guide

The notebook is organized into the following sections:

### 1. Data Collection
- Stock universe definition
- Historical data retrieval
- Data validation and cleaning
- Sector categorization

### 2. Data Preprocessing
- Returns calculation
- Missing data handling
- Outlier detection
- Data filtering

### 3. Risk & Return Calculations
- Expected returns computation
- Covariance matrix calculation
- Volatility analysis
- Downside risk metrics

### 4. Portfolio Optimization
- Mean-variance optimization
- Cluster-based constraints
- Sector exposure limits
- Multiple optimization objectives:
  - Sharpe ratio maximization
  - Sortino ratio maximization
  - Minimum volatility
  - Maximum return

### 5. Monte Carlo Simulation
- 10,000 portfolio simulations
- Efficient frontier generation
- Risk-return analysis
- Portfolio performance comparison

### 6. Visualization
- Interactive plots
- Performance charts
- Sector exposure visualization
- Portfolio weight comparisons
- Efficient frontier plots

### 7. Results Analysis
- Portfolio metrics comparison
- Risk decomposition
- Performance attribution
- Cluster and sector analysis

## Dependencies

The project uses the following main libraries:
- **Data Science**: NumPy, Pandas, SciPy, scikit-learn
- **Financial Analysis**: yfinance, cvxopt
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Development**: Jupyter, Notebook, ipykernel
- **Data Processing**: requests, beautifulsoup4, lxml, html5lib

For a complete list of dependencies and their versions, see `requirements.txt`.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
