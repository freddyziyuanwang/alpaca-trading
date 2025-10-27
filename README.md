# alpaca-trading
Automatically trading 
An automated trading system built with Python and the Alpaca API, capable of fetching real-time market data, generating trading signals based on trend-following strategies, and executing live trades through the Alpaca platform. (in alpaca🦙)

Main include
1. alpaca_connector.py        # Connects to Alpaca API, handles authentication and order execution
2. price_fetcher.py           # Fetches live or historical market data
3.  trend_following_trader.py  # Implements trading logic (e.g. moving average crossover)
4. colab_trading_bot.py       # Runs backtesting or paper-trading in Colab
5.  live_trading_bot.py        # Executes live trades in real market
6. .env                       # (not uploaded yet) Contains API keys and secrets

How to apply to your own:
1. change ALPACA_API_KEY = your key here
2. ALPACA_SECRET_KEY= your secret here
3. ALPACA_BASE_URL= your url here
