# Financial-Mathematics
Weekly exercises of the Stochastic Methods for Finance course A.Y. 2021/2022.

Prof. Martino Grasselli

## W1.Binomial-Model/

The assignment consists in the task of pricing a call option with a Binomial Recursive Tree Model, for two different underlying assets (GOOG and BNTX), using  historical data of prices found on Yahoo Finance, to estimate a call option with maturity 3 months.  

The results are reported both in Excel and in a Jupyter-Notebook written in Julia 1.7.0.

In the excel I used a Binomial Tree with 1 step and one of 30 steps, while in Julia I wrote down a function which allows to estimate the prices for a arbitrary number of steps, which allows to appreciate the convergence for the number of steps that goes to infinite.

## W2.Call-Put_Parity/

The assignment consists in the task of pricing the dividend, first computing the discount rate using a Box-Spread strategy, and then through the pricing of a forward contract, pricing the dividend.

The results are reported both in Excel and in a Jupyter-Notebook written in Julia 1.7.0.

In the excel I computed the results for 1 month maturity, while in Julia I wrote down a function which allows to estimate the discount rate and the dividend for each maturity.

## W2.Black-Scholes_Binomial/

The assignment consists in the task of prooving the convergence of the Binomial Recursive Tree model expectation for the Call option price to the Black-Scholes formula. 

The results are reported both in Excel and in a Jupyter-Notebook written in Julia 1.7.0. In particular, while for the Binomial Model I used the function already used in W1.Binomial-Model, for the Black-Scholes price I used the function blsprice of FinancialToolBox.

## W3.Greeks/

The assignment consists in the task of computing the greeks surfaces for a call option and verify the presence of the volatility smile.

The results are reported in a Jupyter-Notebook written in Julia 1.7.0. The Data are downloaded using the python package 'yfinance'. The computations are done using FinancialToolBox.

## W4.Value-at-Risk/

The assignment consists in the task of computing the Value at Risk with several methods:
  - Parametric method
  - Parametric method with EWMA volatility
  - Monte Carlo simulation
  - Historical method
  - Historical simulation

The results are reported in a Jupyter-Notebook framework written in Julia 1.7.2.

## W5.MonteCarlo/

The assignment consists in the task of generating a number of simulations of a Geometric Brownian Motion and, using them, computing the price of several types of options, such as:
  - Vanilla Options
  - Asian Options with fixed strike
  - Asian Options with floating strike
  - Lookback Options
  - Barrier Options up-and-in
  - Barrier Options up-and-out
  - Barrier Options down-and-in
  - Barrier Options down-and-out
  - Double Barrier Options

The results are reported in a Jupyter-Notebook framework written in Julia 1.7.2. We used both user provided function and the package FinancialMonteCarlo.jl.
