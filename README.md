# Machine Learning for Algorithmic Trading using Python

The book provides a comprehensive introduction to how ML can add value to the design and execution of algorithmic trading strategies. It is organized in four parts that cover different aspects of the data sourcing and strategy development process, as well as different solutions to various ML challenges.

## Part 1: How to Design a Trading Strategy

The first part provides a framework for the development of trading strategies driven by machine learning (ML). It focuses on the data that power the ML algorithms and strategies discussed in this book, outlines how ML can be used to derive trading signals, and how to deploy and evaluate strategies as part of a portfolio.

### 01 Machine Learning for Trading

This [chapter](01_machine_learning_for_trading) summarizes how and why ML became central to investment, describes the trading process and outlines how ML can add value. It covers:

- How to read this book
- The rise of ML in the Investment Industry 
- Design and execution of a trading strategy
- ML and algorithmic trading strategies: use cases

### 02: Market & Fundamental Data

This [chapter](02_market_and_fundamental_data) introduces market and fundamental data sources and the environment in which they are created. Familiarity with various types of orders and the trading infrastructure matters because they affect backtest simulations of a trading strategy. We also illustrate how to use Python to access and work with trading and financial statement data. 

In particular, this chapter will cover the following topics:
- How market microstructure shapes market data
- How to reconstruct the order book from tick data using Nasdaq ITCH 
- How to summarize tick data using various time, volume and dollar bars
- How to work with eXtensible Business Reporting Language (XBRL)-encoded electronic filings
- How to parse and combine market and fundamental data to create a P/E series
- How to access various market and fundamental data sources using Python


### 03: Alternative Data for Finance

This [chapter](02_market_and_fundamental_data) outlines categories and describes criteria to assess the exploding number of alternative data sources and providers. It also demonstrates how to create alternative data sets by scraping websites, for example to collect earnings call transcripts for use with natural language processing (NLP) and sentiment analysis algorithms in the second part of the book. More specifically, this chapter covers:

- How the alternative data revolution has unleashed new sources of information
- How individuals, business processes, and sensors generate alternative data
- How to evaluate the proliferating supply of alternative data used for algorithmic trading
- How to work with alternative data in Python, such as by scraping the internet
- Important categories and providers of alternative data

### 04: Research & Evaluation of Alpha Factors

[Chapter 4](04_alpha_factor_research) provides a framework for understanding how factors work and how to measure their performance, for example using the information coefficient (IC). It demonstrates how to engineer alpha factors from data using Python libraries offline and on the Quantopian platform. It also introduces the `zipline` library to backtest factors and the `alphalens` library to evaluate their predictive power. More specifically, this chapter covers:

- How to characterize, justify and measure key types of alpha factors
- How to create alpha factors using financial feature engineering
- How to use `zipline` offline to test individual alpha factors
- How to use `zipline` on Quantopian to combine alpha factors and identify more sophisticated signals
- How the information coefficient (IC) measures an alpha factor's predictive performance
- How to use `alphalens` to evaluate predictive performance and turnover
 

### 05: Strategy Evaluation & Portfolio Management

Testing a strategy requires simulating the portfolios generated by an algorithm to verify its performance under market conditions. Strategy evaluation includes backtesting against historical data to optimize the strategy's parameters, and forward-testing to validate the in-sample performance against new, out-of-sample data and avoid false discoveries from tailoring a strategy to specific past circumstances. This [chapter](05_strategy_evaluation) introduces several approaches to optimizing portfolios that include the application of machine learning (ML) to learn hierarchical relationships among assets. 

More specifically, in this [chapter](05_strategy_evaluation), we cover 
- How to build and test a portfolio based on alpha factors using zipline
- How to measure portfolio risk and return
- How to evaluate portfolio performance using pyfolio
- How to manage portfolio weights using mean-variance optimization and alternatives
- How to use machine learning to optimize asset allocation in a portfolio context


## Part 2: Machine Learning Fundamentals

The second part covers the fundamental supervised and unsupervised learning algorithms and illustrates their application to trading strategies. It also introduces the Quantopian platform where you can leverage and combine the data and ML techniques developed in this book to implement algorithmic strategies that execute trades in live markets.

### 06: The Machine Learning Process

this [chapter](06_machine_learning_process) sets the stage by outlining how to formulate, train, tune and evaluate the predictive performance of ML models as a systematic workflow. It covers:

- How supervised and unsupervised learning using data works
- How to apply the ML workflow
- How to formulate loss functions for regression and classification
- How to train and evaluate supervised learning models
- How the bias-variance trade-off impacts prediction errors
- How to diagnose and address prediction errors 
- How to train a model using cross-validation to manage the bias-variance trade-off 
- How to implement cross-validation using scikit-learn
- Why the nature of financial data requires different approaches to out-of-sample testing

### 07: Linear Models for Regression & Classification

Linear models are applied to regression and classification problems with the goals of inference and prediction. Numerous asset pricing models that have been developed by academic and industry researchers leverage linear regression. Applications include the identification of significant factors that drive asset returns, for example, as a basis for risk management, as well as the prediction of returns over various time horizons. Classification problems, on the other hand, include directional price forecasts. [Chapter 07](07_linear_models) covers the following topics:

- How linear regression works and which assumptions it makes
- How to train and diagnose linear regression models
- How to use linear regression to predict future returns
- How use regularization to improve the predictive performance
- How logistic regression works
- How to convert a regression into a classification problem

### 08: Linear Time Series Models

 This [chapter](08_time_series_models) focuses on models that extract signals from previously observed data to predict future values for the same time series. The time dimension of trading makes the application of time series models to market, fundamental, and alternative data very popular. 
 
 We present tools to diagnose time series characteristics, including stationarity, and extract features that capture potential patterns. Then it introduces univariate and multivariate time series models and how to apply them to forecast macro data and volatility patterns. It concludes with the concept of cointegration and how to apply it to develop a pairs trading strategy.

In particular, we will cover the following topics:
- How to use time series analysis to diagnose diagnostic statistics that inform the modeling process
- How to estimate and diagnose autoregressive and moving-average time series models
- How to build Autoregressive Conditional Heteroskedasticity (ARCH) models to predict volatility
- How to build vector autoregressive models
- How to use cointegration for a pairs trading strategy

### 09: Bayesian Machine Learning

This [chapter](09_bayesian_machine_learning) introduces how Bayesian approaches to machine learning add value when developing and evaluating trading strategies due to their different perspective on uncertainty. More specifically, this chapter covers:

- How Bayesian statistics apply to machine learning
- How to use probabilistic programming with PyMC3
- How to define and train machine learning models
- How to run state-of-the-art sampling methods to conduct approximate inference
- How to apply Bayesian machine learning to compute dynamic Sharpe ratios, build Bayesian classifiers, and estimate stochastic volatility


### 10: Decision Trees & Random Forests
### 11: Gradient Boosting Machines
### 12: Unsupervised Learning

## Part 3: Natural Language Processing

### 13:	Working with Text Data
### 14:	Topic Modeling
### 15:	Word Vector Embeddings

## Part 4: Deep & Reinforcement Learning

### 16:	Deep Learning
### 17:	Recurrent Neural Networks
### 18:	Convolutional Neural Networks
### 19:	Autoencoders & Generative Adversarial Networks
### 20:	Reinforcement Learning

## Part 5: Conclusion

### 21:	What's Next?
