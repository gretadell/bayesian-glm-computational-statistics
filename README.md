# Bayesian GLM Computational Statistics

This repository contains a computational statistics project focused on generalized linear models and Bayesian inference.

The project implements Fisher Scoring from scratch for logistic regression and Poisson regression with canonical link functions.

It also develops a Random Walk Metropolis-Hastings algorithm to estimate Bayesian logistic and Poisson regression models.

The analysis is applied to two datasets: a credit card approval dataset and a hospital length-of-stay dataset.

The project compares frequentist estimates with posterior summaries obtained through MCMC simulation.

Particular attention is given to prior specification, proposal tuning, burn-in selection, and convergence diagnostics.

Trace plots and autocorrelation plots are used to evaluate the stability and mixing behavior of the MCMC chains.

The results highlight the most influential covariates in each model, including credit reports, active accounts, income, medical procedure type, and gender.
