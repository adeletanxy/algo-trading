# Algo Trading

Overview: 
This project focuses on developing a systematic trading algorithm that selects stocks based on specific criteria and applies different trading strategies based on market conditions. The goal is to enhance trading performance by adapting strategies according to stock volatility and market behavior, enabling the algorithm to dynamically adjust to changing market conditions.

Features

## 1. Stock Selection
The stock selection process involves filtering and identifying stocks that meet certain financial and trading criteria. The primary factors considered include:

- Sector Constraints: The algorithm filters stocks based on specific sectors to ensure that only one company is chosen from each sector to ensure diversification.

- Trading Volume: The algorithm assesses trading volumes to ensure liquidity and minimize slippage, making sure that selected stocks can be efficiently bought and sold.

- Volatility: Stocks with high volatility presents opportunities. The algorithm evaluates the price fluctuations of stocks to identify those that are prone to significant price movements, which is ideal for short-term strategies.

- Correlation Analysis: Stocks are further filtered based on their correlation with the broader market or specific sectors. Stocks with lower correlation may be considered for diversification.

## 2. Trading Strategy
   
The core of the algorithm lies in applying different trading strategies based on market conditions. The approach distinguishes between volatile and non-volatile market periods, each requiring different risk management and trade execution strategies.

## 3. Risk Management
Stop-Loss and Take-Profit: To manage risks effectively, the algorithm integrates stop-loss mechanisms. This helps limit losses, ensuring that trades are automatically exited at predefined price levels.

Portfolio Diversification: The algorithm takes a diversified approach to minimize risk by trading multiple stocks across different sectors, thereby reducing the impact of adverse movements in a single stock or sector.

## 4. Performance Metrics
The algorithm evaluates its performance using key metrics such as:

- Sharpe Ratio (risk-adjusted return)
- Maximum Drawdown
- Alpha & Beta
