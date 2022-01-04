# EconTimeSeriesFinalProject
Final Project for Big Data ECON 573

## Research Question
Which **Macroeconomic Factors** affect the *Health* and *Energy* industries?

## Data

The prices were taken from Yahoo Finance.

+ VDE = Vanguard Energy ETF (Energy Industry proxy)
+ VHT = Vanguard Health ETF (Health Industry proxy)

## Executive Summary

The Following Indicators were the most powerful predictors in predicting ETF industry volatility.

+ Initial Jobless Claims (daily)
+ Unemployment Rate (monthly)
+ CPI (monthly)

## Methodology

+ We used the GARCH model to explore the volatility of returns for each ETF
+ We also used the following models:
  + Ridge, Lasso, and Elastic Net Regression
  + Trees and Random Forest

