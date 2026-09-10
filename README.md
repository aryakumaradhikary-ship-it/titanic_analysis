---
title: "README"
output: html_document
---

# Titanic Survival Analysis

An exploratory data analysis and logistic regression model examining 
factors associated with passenger survival on the Titanic, using the 
Kaggle Titanic dataset.

## Contents
- `titanic.Rmd` — full R Markdown analysis (code + narrative)
- `titanic.html` — knitted report (open in a browser to view)
- `Titanic-Dataset(in).csv` — dataset (source: [Kaggle](https://www.kaggle.com/competitions/titanic/data))

## What's in the analysis
- Missing data summary
- Survival patterns by age, sex, passenger class, fare, and family size
- A logistic regression model predicting survival, with odds ratio interpretation

## Key findings
- Sex was the strongest predictor of survival — women survived at a much 
  higher rate than men across every passenger class.
- Passenger class and age were also significant predictors, consistent 
  with lifeboat access and evacuation priority.
- Fare and family size showed patterns in the raw data, but fare lost 
  significance once class was controlled for in the model.
- The logistic regression model correctly classified about 80% of 
  passengers in the training data.

## Tools
R, tidyverse (dplyr, ggplot2), R

## Link to the html document with analysis and findings:
https://aryakumaradhikary-ship-it.github.io/titanic_analysis/titanic.html
