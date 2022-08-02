---
layout: page
title: Assignment 1
description: Project Ideas
---

1. Optimise the following function using JAX autograd and gradient descent [0.5 marks]

$f(\theta) - [2 3]^T$

2. Generate some data (100 data points) using a univariate Normal distribution with `loc=2.0` and `scale=4.0`. 

    a. Plot a 2d contour plot showing the Likelihood or the Log-Likelihood as a function of `loc` and `scale` [1 mark]
    
    b. Find the MLE parameters for the `loc` and `scale` using gradient descent. [1 mark]

    c. Redo the above question but learn `log(scale)` instead of `scale` and then finally transform to learn `scale`. What can you conclude? Why is this transformation useful? [0.5 mark]

3. Generate some data (1000 data points) using a univariate Normal distribution with `loc=2.0` and `scale=4.0` and using Student-T distributions with varying degrees of freedom (1000 data points corresponding to each degree of freedom). Plot the pdf (and logpdf) at uniformly spaced data from (-50, 50) in steps of 0.1. What can you conclude? [1 mark]

4. Analytically derive the MLE for exponential distribution. Generate some data (1000 data points) using some fixed parameter values and see if you can recover the analytical parameters using gradient descent based solution for obtaining MLE. [1 mark]