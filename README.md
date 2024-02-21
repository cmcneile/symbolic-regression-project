# Investigation of the use symbolic regression in data analysis

In regression some data is fitted to a model function.
An example of linear regression is where some data is fit to
a straight line model

$$y = m x + c$$

where m and c are parameters that are determined from the data

However, many possible complex models are possible.
For example, there could more complex models, for example
there could be a quadratic term.


$$y = a  x^2 + m x + c $$

with fit parameters a,m and c.

There are many more possible fit models such as involving log
or exponential functions. Sometimes physical insight allows
some insight into the correct model.

Symbolic regression is a method to determine the model from
data. Essentially it is an efficient way of searching through the many
different possible models.

For example, this paper uses symbolic regression to extract the
equations of physics from the data with no assumptions.
[AI Feynman](https://www.science.org/doi/10.1126/sciadv.aay2631)

## What the project involves

The Python  [Pysr](https://github.com/MilesCranmer/PySR) library will be
used to investigate symbolic regression.

*  The first part of the project will use data sets with known functions such as linear or quadratic. These will be generated using random numbers with the known function. The symbolic regression will check that the original functions are recovered. (Some starting examples)[https://realpython.com/linear-regression-in-python/]
* The simulated data will then be modified to introduce correlations.
* The algorithm will be tested on real data sets such as
[The Auto MPG dataset](https://www.tensorflow.org/tutorials/keras/regression)
* We will also investigate using symbolic regression for time series.

##  Background reading on symbolic regression


* Wikpedia page on [symbolic regression](https://en.wikipedia.org/wiki/Symbolic_regression).
* [overview of symbolic regression](https://towardsdatascience.com/symbolic-regression-the-forgotten-machine-learning-method-ac50365a7d95)

## Software packages to do symbolic regression.

* Python Pysr [Pysr](https://github.com/MilesCranmer/PySR).
