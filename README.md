# Wine Quality Analysis

## Overview

A statistical analysis of the relationship between physicochemical properties and wine quality, with additional comparison of red and white wine varieties.

The project combines exploratory data analysis, correlation analysis, multiple linear regression, assumption checking, and hypothesis testing to identify which physicochemical characteristics are associated with wine quality and whether red and white wines differ statistically.

## Objectives

- Investigate the relationship between physicochemical properties and wine quality.
- Identify variables associated with higher or lower quality ratings.
- Compare the physicochemical profiles of red and white wines.
- Test whether differences between wine varieties are statistically significant.
- Build a regression model to quantify relationships between predictors and quality.
- Translate statistical findings into practical insights for winemaking.

## Data

The analysis considers physicochemical variables including:

- Alcohol
- Volatile acidity
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- pH
- Sulphates
- Density
- Wine type
- Quality score

## Methods

- Exploratory Data Analysis
- Distribution analysis
- Correlation analysis
- Multiple Linear Regression
- Regression assumption checking
- Variance Inflation Factor (VIF)
- Independent-samples t-tests
- Statistical significance testing
- Comparative analysis of red and white wines

## Key Findings

### Physicochemical Drivers

Alcohol showed the strongest positive relationship with wine quality, while volatile acidity showed a strong negative relationship, particularly for red wine.

Residual sugar and density showed weaker relationships with quality.

### Red vs White Wine

The analysis found statistically significant differences in several physicochemical characteristics between red and white wines.

- White wines showed higher residual sugar and chlorides.
- Red wines showed higher volatile acidity.
- Alcohol, density, and sulphates also showed significant differences between wine types.

### Regression Model

The multiple linear regression model explained approximately 29% of the variability in wine quality.

The reported model included predictors such as alcohol, volatile acidity, residual sugar, chlorides, sulfur dioxide, pH, and sulphates.

The relatively modest R² indicates that physicochemical variables explain only part of wine-quality variation and that other factors, including subjective sensory characteristics, also contribute.

## Business / Industry Implications

The findings can support:

- Fermentation and quality-control decisions
- Monitoring of volatile acidity
- Balancing alcohol and acidity
- Product differentiation between red and white wines
- Batch consistency monitoring
- Data-informed wine production strategies

## Limitations

The regression model explains only part of the variation in quality.

Wine quality is also influenced by sensory and other factors that are not fully represented by physicochemical measurements.

## Tools

- R
- Statistical modelling
- Data visualisation
- Hypothesis testing

## Conclusion

The analysis demonstrates how statistical modelling can be used to connect measurable physicochemical properties with wine-quality ratings.

Alcohol and volatile acidity emerged as particularly important predictors, while the comparison of red and white wines demonstrated significant differences in their physicochemical profiles.
