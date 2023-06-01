# trading-financial-library
This is the python library for the backtesting trading strategies and analyzing financial markets 

<img src="finmarketpy_logo.png?raw=true" width="300"/>

# [finmarketpy (formerly pythalesians)](https://github.com/seniorwebdev01/trading-financial-library)

finmarketpy is a Python based library that enables you to analyze market data and also to backtest trading strategies using
a simple to use API, which has prebuilt templates for you to define backtest. Included in the library

* Prebuilt templates for backtesting trading strategies
* Display historical returns for trading strategies
* Investigate seasonality of trading strategies
* Conduct market event studies around data events
* In built calculator for risk weighting using volatility targeting
* Written in object oriented way to make code more reusable

*Contributors for the project are very much welcome, see below!*

# Merging with pythalesians
I had previously written the open source PyThalesians financial library (which has been merged with this - so can focus on maintaining
one set of libraries). This new finmarketpy library has 
* Similar functionality to the trading part of pythalesians
* Rewritten the API to make it much cleaner and easier to use, as well as having many 
new features. 
* finmarketpy requires the libraries, which I've written chartpy (for charts) and findatapy (for loading market data) to function
* By splitting up into smaller more specialised libraries, it should make it easier for contributors
* Using findatapy, you can download market data easily from Bloomberg, Quandl, Yahoo etc
* Using chartpy, you can choose to have results displayed in matplotlib, plotly or bokeh by changing single keyword!

Points to note:
* Please bear in mind at present finmarketpy is under continual development. The API is heavily documented, but we are
looking to add more general documentation.
* Uses Apache 2.0 licence

# Gallery

Calculate the cumulative returns of a trading strategy historically (see finmarketpy_examples/tradingmodelfxtrend_example.py)

<img src="finmarketpy_examples/gallery/fx-trend-cumulative.png?raw=true" width="750"/>

Plot the leverage of the strategy over time

<img src="finmarketpy_examples/gallery/fx-trend-leverage.png?raw=true" width="750"/>

Plot the individual trade returns

<img src="finmarketpy_examples/gallery/fx-trend-trade-returns.png?raw=true" width="750"/>

Calculate seasonality of any asset: here we show gold and FX volatility seasonality (see examples/seasonality_examples.py)

<img src="finmarketpy_examples/gallery/gold-seasonality.png?raw=true" width="750"/>

<img src="finmarketpy_examples/gallery/fx-vol-seasonality.png?raw=true" width="750"/>

Calculate event study around events for asset (see examples/events_examples.py)

<img src="finmarketpy_examples/gallery/usdjpy-nfp.png?raw=true" width="750"/>

