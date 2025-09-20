# Wealthmind_Index_Momentum_Scanner_v0.1 Beta

This Momentum Scanner Beta, implemented as index_momentum_scanner.py, is a Python module that analyzes global stock indices
(e.g., S&P 500, Nasdaq, KOSPI) using 1-year data from yfinance. It calculates the 6-month momentum—defined as the percentage 
change in closing prices over 126 trading days—identifying the top 10 performers. This tool, built in Colab with Python 3.12, 
fetches data, handles NaNs, and sorts results, offering insights into recent market trends as of September 19, 2025.Momentum, 
as per Jagadeesh and Titman (1993), is the tendency of assets with strong past performance to continue outperforming, and 
underperformers to lag, over intermediate horizons (3-12 months). Their research, based on U.S. stock data from 1965-1989, 
suggests this anomaly arises from investor underreaction to new information, driving price continuation. The Scanner 
operationalizes this by quantifying 6-month price trends, aligning with their finding that momentum strategies can yield
significant returns, though with higher risk. By focusing on indices, it extends this concept globally, providing a 
practical tool for identifying potential investment opportunities based on historical price momentum.

