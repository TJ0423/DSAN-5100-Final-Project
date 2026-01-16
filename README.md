# Applied Statistical Inference and Resampling Methods

## Overview
This project demonstrates applied statistical inference workflows using real-world datasets, with an emphasis on hypothesis testing, uncertainty quantification, and reproducible analysis. The goal is to illustrate how classical statistical tests and resampling-based methods can be used to support reliable conclusions when data limitations and distributional assumptions are present.

## Data
The analysis uses real-world observational data with heterogeneous group structures and imperfect distributional properties. The dataset is suitable for illustrating common challenges in applied policy and social data analysis, including unequal sample sizes and deviations from parametric assumptions.

## Methods
The project implements a range of statistical inference techniques, including:
- Classical hypothesis testing (one- and two-sample t-tests, ANOVA, chi-square tests)
- Explicit formulation of null and alternative hypotheses
- Permutation tests to construct empirical null distributions
- Bootstrap procedures to quantify uncertainty and sampling variability
Both manual resampling implementations and built-in statistical functions in R are used to enhance transparency and methodological understanding.

## Key Outputs
Key outputs include test statistics, p-values, confidence intervals, and visualizations of null and bootstrap distributions. Results are interpreted with attention to underlying assumptions and limitations, emphasizing responsible statistical inference in applied settings.

## Reproducibility
All analyses are fully reproducible. Code is organized in a clear, step-by-step workflow with documented assumptions and comments. Random seeds are set where applicable to ensure consistent results.

## File Structure
- `Report/`: Main analysis and results
- `Data and Code/`: Input datasets and mean code of the project
