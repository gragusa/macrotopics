Course Description 
==================

**Topics in Macroeconometrics** aim is to endow students with a working knowledge of the modern econometric methods used in macroeconomics and, to some extent, in finance.

Topics range from classic time series concepts such as linear univariate and multivariate processes (ARMA, VAR) to techniques that have only recently entered the applied macroeconomist' toolbox (Bayesian VAR and Factor Models).

Students need to be familiar with econometric theory at the level of Advanced Econometrics (246PP).

Texbook and Readings 
====================

The main references for this courses are:

-   Brockwell, Peter J. and Richard A. Davis, *Introduction to Time Series and Forecasting*, Springer, 2002

-   Enders, Walter, *Applied econometric time series*. John Wiley & Sons, 2008

-   Hamilton, James D., *Time Series Analysis*, Princeton University Press, 2005


The level of these textbook goes from (relatively) easy (Brockwell and Davis) to difficult (Hamilton). The level of the class is probably in between the level of these two books. Enders' book has many applications of many time series concepts introduced during lectures.

I will provide handouts to highlight challenging aspects of a topic or present material not covered by the references. 

Other references useful for specific part of the course will be posted here!


Teams Channel
===============================

The class has is own [Teams channel](https://teams.microsoft.com/l/team/19%3azQJE2HZpw-bdHBPjK-02bjJ4t5rWHC9ZNMeW3G-jGvU1%40thread.tacv2/conversations?groupId=dd35d7b2-31bb-44b3-b013-412a908eecb8&tenantId=c7456b31-a220-47f5-be52-473828670aa1). I will use it extensively for important communication.

Lectures
========

| Day       | Time  | Classroom |
|-----------|-------|-----------|
| Tuesday   | 14:45 | P1        |
| Wednesday | 12:15 | P1        |

Lectures will be streamed live on Teams. A link to the stream will be made available on the [Teams channel] a few hours before the start of each class. Lectures will not be recorded, and in-person should be considered the standard way of attendance

Software
========================

![julia](https://julialang.org/assets/infra/logo.svg)

The emphasis of the course is on methods and the analysis of real dataset. The best way to understand time series concepts is to write lots of code implementing the various techniques discussed in class on real macro e financial data. The computer language used in this course is [Julia](https://julialang.org).

Exams 
=====

The final grade depends on a series of homework assignments.


Course Outline 
--------------

1.  From Cross-Section to Time Series: asymptotic theory under serial correlation

2.  Stationary Process

    1. Linear processes
    
    2. The Wold representation theorem

    3. ARMA processes: estimation and forecasting

    4. ARIMA models for non-stationary time series

3.  Multivariate Time Series

    1.  Vector Auto-Regressions (VAR)

    2.  Structural VARs: identification

    3.  Structural impulse responses

4.  The Bayesian paradigm

    1.  Likelihood, prior, and posterior

    2.  Bayesian computations

    3.  Applications: Bayesian VAR


6.  Factor models and High Dimensional Econometrics

    1.  Principal components

    2.  Dynamic factor models

    3.  Ridge and Lasso


[Teams Channel]: https://teams.microsoft.com/l/team/19%3azQJE2HZpw-bdHBPjK-02bjJ4t5rWHC9ZNMeW3G-jGvU1%40thread.tacv2/conversations?groupId=dd35d7b2-31bb-44b3-b013-412a908eecb8&tenantId=c7456b31-a220-47f5-be52-473828670aa1


## Pluto's Notebook

- [Working with Auto-Regressive](/ar/)
- [Estimating Auto-Regressive: conditional and full likelihood](/ar_like/)