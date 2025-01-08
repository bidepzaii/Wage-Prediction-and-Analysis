# Wage Prediction and Analysis

## Overview

This project focuses on exploring the relationships between education, work experience, and wages using statistical methods and linear regression models. The dataset includes socio-economic factors and demographic variables, enabling the identification of key predictors for wages while addressing potential biases and multicollinearity in the model.

---

## Features

### **Exploratory Data Analysis**
- Statistical summaries of key variables (education, experience, wages).
- Visualization techniques: histograms, boxplots, scatterplots, and heatmaps.
- Analysis of correlations to identify potential predictors and collinearity issues.

### **Model Implementation**
- **Baseline Model:** Multiple Linear Regression (MLR) with education and experience as predictors.
- **Improved Model:** Inclusion of additional variables (e.g., IQ, marital status, urban living) to address omitted variable bias (OVB).
- **Full Model:** Comprehensive analysis with all potential predictors.

### **Model Evaluation**
- Assessment of R-squared, Adjusted R-squared, and Standard Error of Regression (SER).
- F-tests to evaluate the significance of predictors.
- Residual analysis to validate OLS assumptions, including linearity, exogeneity, independence, and constant variance.

---

## Key Insights

- **Baseline Model:** Education and experience positively correlate with wages, but the model explained only 14% of the wage variance.
- **Improved Model:** Incorporating additional predictors improved model performance (Adjusted R-squared increased to 0.227).
- **Omitted Variable Bias:** Variables like IQ, marital status, and urban living were significant contributors to wage variation.
- **Final Model:** Addressed multicollinearity and validated assumptions for robust insights.

---

## Repository Structure

