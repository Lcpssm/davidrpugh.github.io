---
layout: page
title: pyCollocation
date: 
modified: 2015-07-14
excerpt:
tags: [python, economics, boundary value problems]
image:
  feature:
---

## Overview

Python package for solving initial value problems (IVP) and two-point boundary value problems (2PBVP) using the collocation method with various basis functions. Currently I have implemented the following basis functions:

* Orthogonal polynomials: [Chebyshev](http://en.wikipedia.org/wiki/Chebyshev_polynomials), [Laguerre](http://en.wikipedia.org/wiki/Laguerre_polynomials), [Legendre](http://en.wikipedia.org/wiki/Legendre_polynomials), and [Hermite](http://en.wikipedia.org/wiki/Hermite_polynomials).

The source code for the pyPWT package is hosted on [GitHub](https://github.com/davidrpugh/pyCollocation).

## Installation

Assuming you have [pip](https://pypi.python.org/pypi/pip) on your computer (as will be the case if you've installed [Anaconda](http://quant-econ.net/getting_started.html#installing-anaconda)) you can install the latest stable release of ``pycollocation`` by typing
    
{% highlight bash %}
    $ pip install pycollocation
{% endhighlight %}

at a terminal prompt.

## Example notebooks

### Economics

There are a number of example notebooks that demonstrate how to use the library to solve seminal models in the economics literature.

* [Solow model of economic growth](http://nbviewer.ipython.org/github/davidrpugh/pyCollocation/blob/master/examples/solow-model.ipynb)
* [Ramsey model of optimal savings](http://nbviewer.ipython.org/github/ramseyPy/ramseyPy/blob/master/examples/ramsey-model.ipynb)
* [Spence model of costly signaling](http://nbviewer.ipython.org/github/davidrpugh/pyCollocation/blob/master/examples/spence-model.ipynb)
* [Kiyotaki and Moore model of credit cycles](http://nbviewer.ipython.org/github/davidrpugh/pyCollocation/blob/master/examples/credit-cycles.ipynb)

### Physics

* [A simple heat exchanger](http://nbviewer.ipython.org/github/davidrpugh/pyCollocation/blob/master/examples/heat-exchanger.ipynb) 

More notebooks will be added in the near future (hopefully!)
