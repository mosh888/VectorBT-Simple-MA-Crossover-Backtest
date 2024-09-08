MA Crossover Strategy Backtest with Benchmark Comparison 

This repository contains a Python script that backtests a simple moving average (MA) crossover strategy on Nasdaq 100 Futures (NQ=F) and compares its performance against a buy-and-hold strategy on S&P 500 Futures (ES=F). The backtest is conducted using the VectorBT library, which allows for efficient data retrieval, strategy implementation, and performance analysis. 

Features: 

Moving Average Crossover Strategy: 

- The script applies a 10-period fast MA and a 50-period slow MA on NQ=F (Nasdaq 100 Futures) to generate buy and sell signals. 
- Benchmark Comparison: The strategy's performance is compared against a benchmark buy-and-hold strategy on ES=F (S&P 500 Futures). 
- Visualization: The script generates visual comparisons of portfolio values and includes relevant performance statistics for both the strategy and the benchmark. 
- Customizable Timeframe: Users can adjust the start and end dates and the data interval (e.g., hourly) to backtest different periods. 

Requirements: 
- Python 3.7 or higher 
- vectorbt library 
- matplotlib library
