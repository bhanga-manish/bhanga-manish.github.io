---
title: "Calculating Multiple Linear Regression Parameters"
date: 2020-05-26
tags: [Python, Linear Regression]
excerpt: "Learn how python libraries calculates the estimated parameters for Multiple Linear Regression"
---

Linear regression is used to find a linear relationship between a target and one or more predictors.
Multiple linear regression explains the relationship between one dependent variable (y) and two or more independent variables (x1, x2, x3… etc).
Y(pred) = b0 + b1*x1 + b2*x2+...+bn*xn

With the growing data science community and open source projects. There are enough packages and libraries to help anyone from getting started to deploy Multiple Linear Regression models into production. These packages easily help us in computing coefficients.It will be a nice thought to learn how these coefficients are computed. In this blog we’ll see how some of the packages use Normal Equations to compute the parameters.

The process of derivation is more convenient with the help of vectors and matrices.

<img src="{{ site.url }}{{ site.baseurl }}/images/MLR/MLR_matrix_form.png" alt="Matrices and vectors">

With this compact notation, the linear regression model can be written in the form.

$$ Y = Xß + ∑ $$

We want to find the “best” β in the sense that the sum of squared residuals is minimized. The smallest possible value so that the sum of squares could be zero. If value of i reached zero, then.

$$ Y^^ = Xß^^ $$