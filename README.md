# Parametric Health Insurance Pricing Case Study

This project develops a parametric health insurance pricing model inspired by the SOA Student Research Case Study framework.

## Objective

The objective is to design a transparent parametric insurance product where payouts are triggered by a composite health risk index rather than traditional claim assessment.

The model focuses on:

- Trigger design
- Health Index construction
- Parametric payout calculation
- Monte Carlo simulation
- Expected payout estimation
- Premium adequacy testing

## Data

The analysis uses health-related indicators from the SOA case study dataset:

- Blood pressure
- Diabetes prevalence
- Cholesterol indicators

These indicators are used to construct a composite Health Index.

## Methodology

The workflow includes:

1. Data cleaning and preparation
2. Correlation analysis
3. Principal Component Analysis (PCA)
4. Construction of a PCA-based Health Index
5. Trigger threshold selection using the 90th percentile
6. Parametric payout calculation based on excess over threshold
7. Monte Carlo simulation
8. Premium calculation using the equivalence principle
9. Sensitivity testing on threshold, payout factor, and loading assumptions

## Key Assumptions

- Trigger threshold: 90th percentile of the historical Health Index
- Payout formula: payout factor x excess over threshold
- Basic premium: expected payout
- Gross premium: basic premium with loading for expenses, risk margin, and profit

## Tools

- Python
- pandas
- numpy
- matplotlib
- scikit-learn
- openpyxl

## Key Learning

This project demonstrates how actuarial pricing concepts can be applied to parametric insurance design, including trigger construction, basis risk consideration, Monte Carlo simulation, expected payout estimation, and premium adequacy testing.
