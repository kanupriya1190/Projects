## Notable Projects

1. **Stock Volatility Analysis Using GARCH Model**
    - **Description**: In this project, a GARCH(2,1) model was applied to analyze volatility in key tech stocks (AAPL, MSFT, NVDA) and the NASDAQ Composite Index (^IXIC). The data preprocessing involved stationarity checks and differencing to make the time series suitable for GARCH modeling. The model revealed strong volatility persistence (β > 0.70) and a significant impact of market shocks (α), indicating substantial time-dependent risk factors in these assets. To validate the model, a Ljung-Box test was performed on the residuals, confirming minimal autocorrelation and ensuring that the model effectively captured the volatility patterns without leaving out any predictable structure. These findings highlight the utility of GARCH modeling for accurate financial time series analysis.
    - **Skills**: Time Series Analysis, GARCH Model, Ljung-Box Test, Python, Financial Data Analysis
    - [[GARCH project.ipynb](https://github.com/kanupriya1190/Projects/blob/e2e281d9b0c82c5d71c46ef65fd90a67a5479e5a/GARCH%20project.ipynb)](#)

2. **Portfolio Risk Analysis and Optimization**
    - **Description**: This project involves using a Random Forest Regressor to predict SOFI stock prices, achieving a Mean Squared Error (MSE) of 0.55, which indicates strong predictive accuracy. Additionally, Monte Carlo simulations and Capital Asset Pricing Model (CAPM) analysis were applied to optimize a diversified portfolio. The portfolio analysis provided key insights into risk-adjusted returns, with calculated alpha and beta values reflecting the portfolio’s sensitivity to market movements relative to Nasdaq and S&P 500.
    - **Skills**: Machine Learning (Random Forest), Monte Carlo Simulations, CAPM, Python, Financial Data Analysis
    - [[Repository Link](https://github.com/kanupriya1190/Projects/blob/d6a384d7850cd7f83c3a4b23af6a9083c5e0a1ae/stocks%20trading.ipynb)](#)
  
3. **Cloud-Based Handwritten Digit Recognition with Interactive GUI**
    - **Description**: This project develops a machine learning model for handwritten digit recognition, achieving 93% accuracy. The model was trained using a Random Forest classifier on digit images and deployed on Google Cloud. An interactive GUI was created to allow users to upload their handwritten digit images, which are then processed by the cloud-deployed model to return real-time predictions. This project demonstrates end-to-end deployment, from model training to user interaction through a simple, accessible interface.
    - **Skills**: Machine Learning, Cloud Deployment, GUI Development, REST API Integration
    - [[[Repository Link]](https://github.com/kanupriya1190/Projects/blob/1185a9814e8398bc1efef759824ddafb76aca7ec/Cloud%20Computing%20.ipynb)](#)

4. **Statistical Arbitrage and Portfolio Optimization with Alpaca Broker API**
    - **Description**: This project implements a statistical arbitrage strategy using cointegrated stock pairs, optimized with the Alpaca Broker API for real-time data and trade execution. Statistical tests identified pairs with strong cointegration, allowing for a mean-reverting trading strategy. Portfolio optimization was conducted to achieve minimum variance allocation, resulting in a highly efficient portfolio of 0 SPY, 1252 VOO, 13 BND, and 3 AAPL. The analysis includes candlestick charts to visualize price movements, along with calculations of mean continuously compounding returns to assess profitability over time. Comprehensive visualizations illustrate cointegration, portfolio allocations, and performance, providing insights into the strategy’s effectiveness and risk characteristics.
    - **Key Results**: The optimized portfolio allocation achieved with this strategy provides balanced exposure across key assets, informed by both variance reduction and statistical relationships within the selected stock pairs.
    - **Skills**: Statistical Arbitrage, Portfolio Optimization, Cointegration Analysis, API Integration, Financial Data Visualization
    - [[[Repository Link]](https://github.com/kanupriya1190/Projects/blob/1185a9814e8398bc1efef759824ddafb76aca7ec/Broker%20API.ipynb)](#)
