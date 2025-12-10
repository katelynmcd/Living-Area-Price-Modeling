# living-area-price-modeling
Modeling how living area impacts home prices across neighborhoods using interaction terms, centering, and regression diagnostics.

## Problem Statement
Century 21 Ames wants to understand how the value of additional living area differs across Brookside, Edwards, and North Ames in Ames, Iowa. Realtors typically discuss square footage in 100 sq ft increments, so the goal of this project is to model how each extra 100 sq ft affects home sale price and determine whether that relationship changes depending on neighborhood.

## Overview
- Analyzed home sale prices using living area (in 100 sq ft units) and neighborhood.
- Fit and compared multiple models: base model, interaction model, log-linear model, and log–log model.
- Ran full diagnostic checks to evaluate linearity, variance, normality, and influential observations.
- Selected a centered log-linear interaction model for its interpretability and improved assumptions.
- Interpreted neighborhood-specific slopes to understand how much value additional space adds in each location.

## Skills Used
- **R Programming:** tidyverse, dplyr, ggplot2
- **Regression Modeling:** linear regression, log-linear regression, interaction terms
- **Model Assessment:** AIC, R², confidence intervals
- **Diagnostics:** residual analysis, leverage, Cook’s distance, studentized residuals
- **Data Preparation:** feature creation (Gr100, Gr100.c), filtering, factor encoding
- **Communication:** interpreting coefficients and neighborhood effects
