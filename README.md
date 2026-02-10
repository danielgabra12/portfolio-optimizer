Overview

  This project is a Python-based financial forecasting engine that models and predicts short-term asset behavior using statistical time series methods.

  It ingests portfolio data from Excel, fits multiple forecasting models, and generates 20-business-day forward projections to support data-driven investment decisions.

  The goal was to build a scalable, production-style forecasting pipeline rather than just run isolated models.

What This Project Demonstrates

  Applied time series modeling in a financial context

  Model comparison and parameter tuning

  Parallelized computation for scalability

  Clean data ingestion pipeline from real-world Excel input

  Business-oriented forecasting (forward-looking horizon)

  Structured, reusable modeling framework

Models Implemented

  SARIMAX (ARIMA-based forecasting)
  
  Holt-Winters Exponential Smoothing
  
  Theta Model
  
  Each model is fitted programmatically and designed to handle financial time series with realistic trading-day constraints.
  
  Key Features
  
  Automatic Excel file detection
  
  Minimum observation filtering (1 trading year)

  Reduced ARIMA grid search for computational efficiency
  
  Parallel model execution using joblib
  
  Business-day forecast generation
  
  Warning management and model stability handling

Tech Stack

  Python
  
  Pandas
  
  NumPy
  
  Statsmodels
  
  Joblib
  
  Matplotlib

How It Works
  
  Loads portfolio data from Excel
  
  Filters assets with sufficient historical data
  
  Performs parameter grid search (ARIMA)
  
  Fits multiple forecasting models
  
  Generates 20-business-day forecasts
  
  Outputs structured predictions for portfolio analysis

Why This Project Matters

  Financial decisions require forward-looking modeling. This project demonstrates the ability to:
  
  Translate quantitative theory into applied forecasting
  
  Structure clean analytical pipelines
  
  Balance model complexity with computational efficiency
  
  Build scalable, reusable code rather than one-off scripts
  
  It reflects practical quantitative skills applicable to data science, quantitative finance, and analytical roles.

Potential Extensions

  Rolling backtesting framework
  
  Model selection via AIC/BIC comparison
  
  Integration with mean-variance optimization
  
  Performance metrics (RMSE, MAE)
  
  Deployment as a modular package
