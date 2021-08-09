# Project 3: Bitcoin Genie 9000

![Bot_Image](Images/trading_bot_9000.jpeg)

---
### Team Members: Chrishan de Almeida, Greg Buiter
### Date: August 9, 2021

## Overview: 

An easy-to-integrate crypto trading bot that can connect to a trading platform and execute buy and sell orders with the intention of maximizing profits by capitalizing on short term technical trends.  Our intention was to develop a simple bot that could autonomously execute trades in real time using the Binance API and then adding functionality and sophistication as we continued to develop our code.  Our development roadmap is outlined below using the cupcake, cake and wedding metaphor for design evolution.

## Development Roadmap (Feature sets):

### Basic (Cupcake):

- Can connect to crypto trading platform (Binance)
- Can trade only Bitcoin
- Uses preset trading logic based on technical indicators (BollingerBands)

### Intermediate (Birthday Cake):

- Can connect to crypto multiple trading platform (ex. Kraken, Crypto.com) 
- Twitter user followers is considered (>1M followers)
- Incorporate trading logic based on additional technical indicators: RSI, VWAP & Sentiment analysis
- Fully functioning GUI (Tkinter)

### Advanced (Wedding Cake):

- Integrates into any trading platform
- Can trade all cryptos
- Uses sophisticated trading algorithm based on machine learning (regression or ARIMA)
- Considers retweets (>5M retweets)
- BOT identifies unknown influencers based on past tweets and correlation to Crypto price movements (accuracy score)
- advanced GUI using Flask/AWS

## Post Mortem: 

### Exceeded Expectations:
- Incorporated a "cool off period" to reduce BOT's ability to react to trade signals for a specified amount of time. Our cool down period was abitrarily selected at 25% of our Bollinger Band window.
- introduced GUI into "cupcake" version using "Tkinter"

### Fell Short of Expectations:
- RSI was not incorporated in "cupcake" version of Trading BOT
- websocket limit error
- taLib integration in Jupyter lab
- miniforge installation





