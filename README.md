# Empirical-Methods-in-Finance
Assignments for the Empirical Methods in Finance class of Spring 2021 with Professor Florian at HEC Lausanne Ielpo. 

## Assignment 1

This report aims to analyze the stock performance of the S&P500 index’s constituents. We will first briefly explain what the S&P500 stock market index is, and how its constituents enter and leave the index. Then, we will analyze the skewness and kurtosis of the individual companies to get a better idea of their distribution characteristics. Next, we will conduct various hypothesis tests starting with the Jarque & Bera test and the Kolmogorov & Smirnov test to check for normality of distribution followed by the Ljung Box test to check for potential auto-correlations. Finally, we will run a regression on each individual stock, with the return on the market portfolio as the independent variable. Finally, we will briefly explain the significance of these empirical results in the context of investment strategies.

Our data set includes the prices of 452 out of the 500 constituents of the S&P500 index, as well as the value of the index itself, over an unspecified period of time, indexed at 100 in time 0.

## Assignment 2

This report is divided into two parts. The first part aims to manipulate times series of various crypto-currencies (i.e. Bitcoin, Ethereum and Monero). We will first test for stationarity using the Dickey Fuller test, then check for co-integration among our crypto-currencies, and finally try to implement a pair-trading strategy using the results found previously. The second part will aim to test again the stationarity of four new time series (i.e. US Dollar in trade weighted terms, Gold, the level of VIX index and Bitcoin), using the Augmented Dickey Fuller test and the Kwiatkowski Phillips Schmidt Shin (KPSS) test. After transforming the non-stationary series into stationary ones, we will try to build a Vector Auto-Regressive (VAR) model, by deciding the number of lags using various information criteria. Thereafter, we will determine the Impulse Response Function between our assets. Finally, we will estimate an unconstrained and constrained VAR(1) model, and check whether there are any statistical differences between them.

## Assignment 3

This report consists of two different parts. In the first part, we discuss three different types of GARCH models (GARCH, EGARCH and GARCH-GJR) to estimate the time varying volatility of the log-returns of three different time series (S&P 500, BCOM Commodity index and Apple).
GARCH models allow us to perform a time-varying volatility estimation, as well as to take into account persistence in volatility. These are particularly interesting features of volatility that are present in empirical data. In addition to the standard GARCH model, we are using two extension, EGARCH and GARCH-GJR which allow us to take into account the asymmetry of volatility.
In the second part, we are using the famous Heston and Nandi model to price call options on the S&P 500. This model allows us to take into account time varying volatility in the pricing of the calls. Using a time varying volatility model is important when it comes to option pricing because we know that empirically, volatility is indeed time varying. Thus, this kind of model offers a more precise estimation of the price of options than standards model like Black-Scholes or the Binomial Model who assume constant volatility.
