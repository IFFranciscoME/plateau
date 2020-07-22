
# Abstract
Library for implementing the "Plateau Finding", a technique for trading systems optimization.

# Description
_plateau finding_ is an optimization technique that, in the parameter space of a trading system,
looks for "plain areas" in that sapce (a surface for the case of 3 dimensions) in order to pick the
 highest of the points in the area and consider it as a local optimum, and use it in the trading system
  with the benefit of out of sample stability in the performance metric defined. 
 All of this in contrast with "hill climbing" type of optimization algorithms, that look for a "high peak"
  (global optimum) and present high sensibility to parameter value changes and reflect that in a greater
  out of sample deviation of values found in sample. In a trading context, is better to have several 
"neighbooring" configurations that produces "good and stable" results all of them, than, having one 
configuration with "the best" result but with neighbooring configurations producing "poor" results.

# Instructions for demo
Instructions for running this project.

1. Install dependencies

    > $ pip install -r requirements

2. Select parameters
    
    In the _data.py_ you can select the input parameters for the examples. 

# Author
Msc Juan Francisco Muñoz Elguezabal - franciscome@iteso.mx
