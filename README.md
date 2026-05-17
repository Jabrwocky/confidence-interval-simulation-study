# Confidence Interval Simulation Study

This repository contains a mathematical statistics project focused on confidence intervals, repeated-sampling interpretation, and simulation-based evaluation of interval performance.

The project combines:
- theoretical derivation,
- historical/statistical context,
- Monte Carlo simulation,
- and empirical coverage analysis.

Using R and Quarto, the analysis compares confidence interval procedures for both Bernoulli and exponential models, with particular attention to:
- empirical coverage probability,
- interval precision,
- large-sample approximation behavior,
- and finite-sample performance.

## Topics Covered

### Bernoulli Model
- Derivation of the Wald confidence interval for a population proportion
- Discussion of Clopper–Pearson exact intervals
- Coverage simulations across varying sample sizes
- Analysis of interval width vs. precision tradeoffs

### Exponential Model
- MLE derivation for the exponential rate parameter
- Fisher information and asymptotic normal intervals
- Exact pivotal chi-square confidence intervals
- Simulation comparison of normal vs. pivotal interval performance

## Methods
- Monte Carlo simulation (10,000 repetitions per setting)
- Coverage probability estimation
- Interval length analysis
- Large-sample approximation assessment

## Tools Used
- R
- Quarto
- Statistical simulation
- Mathematical derivation and asymptotic theory

## Files
- report.pdf — Final written report containing derivations, simulations, tables, and figures
- analysis.qmd — Quarto source file used to generate the report
- code/ — Supporting R code and simulation scripts

This project was completed as part of coursework in mathematical statistics and is included as a public example of statistical theory, simulation, and reproducible analytical reporting.
