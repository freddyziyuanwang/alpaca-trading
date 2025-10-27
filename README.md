# alpaca-trading
Automatically trading 
An automated trading system built with Python and the Alpaca API, capable of fetching real-time market data, generating trading signals based on trend-following strategies, and executing live trades through the Alpaca platform. (in alpaca🦙)

Main include
├── alpaca_connector.py        # Connects to Alpaca API, handles authentication and order execution
├── price_fetcher.py           # Fetches live or historical market data
├── trend_following_trader.py  # Implements trading logic (e.g. moving average crossover)
├── colab_trading_bot.py       # Runs backtesting or paper-trading in Colab
├── live_trading_bot.py        # Executes live trades in real market
└── .env                       # (not uploaded yet) Contains API keys and secrets

How to apply to your own:
change ALPACA_API_KEY= your key here
ALPACA_SECRET_KEY= your secret here
ALPACA_BASE_URL= your url here
