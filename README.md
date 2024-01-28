# Design and Analysis of Experiments Project

## Overview
This project encompasses a comprehensive toolkit for experiment design and analysis. Developed at MIT, it offers robust solutions for a wide range of statistical analyses.

## Functionalities

### ANOVA Analysis
- Function: `anovaAnalysis(data, type)`
- Description: Conducts ANOVA tests (one-way, two-way, repeated measures).
- Outputs: F-statistics, p-values, and graphical summaries.

### t-Test Analysis
- Function: `tTestAnalysis(data, testType)`
- Description: Performs one-sample, independent two-sample, and paired-sample t-tests.
- Outputs: Data distributions with histograms and box plots.

### Monte Carlo Simulations
- Function: `monteCarloSimulation(parameters)`
- Description: Runs simulations to estimate error rates in statistical tests.

### Non-Parametric Tests
- Function: `nonParametricTest(data, testType)`
- Description: Offers non-parametric testing for non-normal data distributions.

### Regression Analysis
- Function: `regressionAnalysis(data, modelType)`
- Description: Performs linear and non-linear regression, including model diagnostics.
- Outputs: Regression coefficients, diagnostics, and residual analysis.

### Multivariate Analysis
- Function: `multivariateAnalysis(data, analysisType)`
- Description: Conducts PCA, Factor Analysis, and other multivariate techniques.

### Data Transformation
- Function: `dataTransformation(data, method)`
- Description: Applies transformations and normalization to data.

### Customizable Plots
- Function: `createPlot(data, plotType)`
- Description: Generates customizable plots like box plots and histograms.

### Error Handling
- Function: `errorCheck(data)`
- Description: Provides error handling for data input issues.

### Interactive Analysis Interface
- Function: `interactiveAnalysis()`
- Description: Offers a GUI for real-time data analysis and visualization.

### Documentation
- Each function is accompanied by comprehensive documentation, including examples and parameter descriptions.

## Usage Example

```R
# Conducting a Two-way ANOVA
results <- anovaAnalysis(yourData, "two-way")

# Performing a Paired-sample t-Test
tTestResult <- tTestAnalysis(yourData, "paired-sample")

# Linear Regression Analysis
regressionResult <- regressionAnalysis(yourData, "linear")
