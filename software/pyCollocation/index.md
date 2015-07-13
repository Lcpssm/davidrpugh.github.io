---
layout: page
title: pyCollocation
date: 
modified: 2015-08-13
excerpt:
tags: [python, economics, boundary value problems]
image:
  feature:
---

[![Build Status](https://travis-ci.org/davidrpugh/pyCollocation.svg?branch=master)](https://travis-ci.org/davidrpugh/pyCollocation)
[![Coverage Status](https://coveralls.io/repos/davidrpugh/pyCollocation/badge.svg?branch=master)](https://coveralls.io/r/davidrpugh/pyCollocation?branch=master)
[![Codacy Badge](https://www.codacy.com/project/badge/4838082c243c48afa392aabc7cce54ab)](https://www.codacy.com/app/drobert-pugh/pyCollocation)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/davidrpugh/pyCollocation/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/davidrpugh/pyCollocation/?branch=master)
[![Latest Version](https://img.shields.io/pypi/v/pyCollocation.svg)](https://pypi.python.org/pypi/pyCollocation/)
[![Downloads](https://img.shields.io/pypi/dm/pyCollocation.svg)](https://pypi.python.org/pypi/pyCollocation/)
[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.17283.svg)](http://dx.doi.org/10.5281/zenodo.17283)

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
