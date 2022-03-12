# Financial-Mathematics
Weekly exercises of the Stochastic Methods for Finance course A.Y. 2021/2022.

Prof. Martino Grasselli

## W1.Binomial-Model

The assignment consists in the task of pricing a call option with a Binomial Recursive Tree Model, for two different underlying assets (GOOG and BNTX), using  historical data of prices found on Yahoo Finance, to estimate a call option with maturity 3 months.  

The results are reported both in Excel and in a Jupyter-Notebook written in Julia 1.7.0.

In the excel I used a Binomial Tree with 1 step and one of 30 steps, while in Julia I wrote down a function which allows to estimate the prices for a arbitrary number of steps, which allows to appreciate the convergence for the number of steps that goes to infinite.
