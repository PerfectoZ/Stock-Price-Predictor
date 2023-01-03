# Stock Price Predictor
> Predict price for various stocks and cryptocurrencies using historical daily data

[![Python Version][python-image]][python-url]
![REST API][rest-api-image]
![Build Status][travis-image]

This Python Notebook aims to predict closing price for stocks using XtremeGradient Boost Machine Learning Algorithm as accurately as possible and
uses AlphaVantage REST API for fetching historical data points

![](header.png)

## Installation

Windows and Mac OS X and Linux :

```sh
pip install numpy
pip install matplotlib
pip install seaborn
pip install jupyter-notebook
pip install scikit-learn
pip install xgboost
```

## Usage example

To run this all you need is a AlphaVantage API Key which can
be found [Here](https://alphavantage.com/)

## Development setup

To Setup the Notebook Install the Above Dependencies and Replace [redacted] with your Alphavantage API Key.

## Release History
* 0.0.3 (WIP)
    * Add Support to search for symbols before requesting data to avoid empty CSV

* 0.0.2
    * Added Support for Cryptocurrency
    
* 0.0.1
    * Basic Skeleton is Ready and running

## Meta

[PerfectoZ](https://github.com/PerfectoZ) – [Email](mandeepsinghtaneja_it20b10_47@dtu.ac.in) – [LinkedIn](https://linkedin.com/in/mandeep-taneja)


## Contributing

1. [Fork it](<https://github.com/PerfectoZ/Geolocational-Data-Analysis/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some New Feature'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[python-image]: https://img.shields.io/badge/Python-3.9.x-blue?style=flat-square
[python-url]: https://npmjs.org/package/datadog-metrics
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[rest-api-image]: https://img.shields.io/badge/REST%20API-V3-orange?style=flat-square
