# Market Maker Lite TDA Repository
<!-- 
[![Website](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)
-->
[![Python Badge](https://img.shields.io/badge/made%20with-python-blue.svg)]()
[![GitHub last commit](https://img.shields.io/github/last-commit/MarketMakerLite/TDA)](https://github.com/MarketMakerLite/TDA/commits/main)
[![Discord](https://img.shields.io/discord/837528551028817930?color=%237289DA&label=Discord)](https://discord.gg/jjDcZcqXWy)

A repository of code that interacts with the TDA-API

### Options-Data
This code loops through a list of tickers to get the entire options chain for each symbol.
It's designed to run all day, and will consistently loop through the list of tickers. 
It will automatically handle the start and end of the trading day, as well as holidays, etc. 

### Installation
* Python 3.8
* pip install -r requirements.txt

### Continuous Integration Testing

This github action allows a developer to push code changes to the repository **and** send those changes to a server. 
This video does a great job explaining how to automatically deploy a github repo to your server
https://www.youtube.com/watch?v=DufTz_ShMVw.

The purpose of integration testing on a scraper like this one is to be able to make adjustments to your without affecting the production code on the far right.
#### Testing of an App that Makes Changes to a Database
![img.png](img.png)
Source: https://realpython.com/python-continuous-integration/

