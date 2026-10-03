# Advanced Statistical Analysis & Hypothesis Testing

## Project Overview

This project demonstrates inferential statistical analysis using Python and Jupyter Notebook. It applies parametric and non-parametric hypothesis tests to a scientific dataset to evaluate statistical significance, compare groups, and interpret findings.

## Objectives

* Perform normality tests using Shapiro–Wilk and Kolmogorov–Smirnov/Lilliefors tests.
* Conduct an independent two-sample Welch's t-test.
* Apply the Mann–Whitney U test.
* Perform One-Way ANOVA and Two-Way ANOVA.
* Conduct Tukey HSD post-hoc analysis for multiple comparisons.
* Calculate 95% confidence intervals.
* Visualize data distributions and compare groups.
* Document null hypotheses, alternative hypotheses, p-values, and conclusions.

## Dataset

**Dataset:** Iris Flower Dataset

The dataset contains 150 observations across three iris species:

* Iris setosa
* Iris versicolor
* Iris virginica

It includes four numerical features:

* Sepal length
* Sepal width
* Petal length
* Petal width

The dataset is provided by scikit-learn.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* SciPy
* Matplotlib
* Seaborn
* Statsmodels
* Scikit-learn

## Statistical Methods

1. **Normality testing:** Shapiro–Wilk and Lilliefors-corrected Kolmogorov–Smirnov test.
2. **Parametric testing:** Independent two-sample Welch's t-test.
3. **Non-parametric testing:** Mann–Whitney U test.
4. **One-Way ANOVA:** Comparison of mean sepal lengths across three species.
5. **Two-Way ANOVA:** Analysis of species and petal-width groups, including their interaction.
6. **Post-hoc testing:** Tukey HSD pairwise comparisons.
7. **Confidence intervals:** 95% confidence interval for the difference between two group means.

## Significance Level

The significance level is set to **α = 0.05**.

* If p-value < 0.05, reject the null hypothesis.
* If p-value ≥ 0.05, fail to reject the null hypothesis.

## Visualizations

The notebook includes:

* Histograms with distribution curves
* Box plots
* Q–Q plots
* Group mean plots with 95% confidence intervals

## Installation

Install the required libraries using:

```bash
pip install pandas numpy scipy matplotlib seaborn statsmodels scikit-learn
```

## How to Run

1. Clone or download this repository.
2. Open `Advanced_Statistical_Analysis.ipynb` in Jupyter Notebook or VS Code.
3. Install the required dependencies.
4. Select the appropriate Python kernel.
5. Run all notebook cells to generate statistical results, tables, plots, and conclusions.

## Key Learning Outcomes

* Understanding statistical hypothesis testing.
* Interpreting p-values and confidence intervals.
* Selecting suitable parametric and non-parametric tests.
* Comparing multiple groups using ANOVA.
* Interpreting post-hoc comparisons.
* Communicating statistical findings using Python.

## Limitations

The Iris dataset is used for educational purposes. The second factor in the Two-Way ANOVA is derived by dividing petal width into narrow and wide groups at the median. Therefore, this analysis demonstrates the method and should not be interpreted as a causal experiment.

## Project Deliverable

The primary deliverable is the Jupyter Notebook:

`Advanced_Statistical_Analysis.ipynb`

It contains the Python implementation, statistical test results, visualizations, hypotheses, confidence intervals, and interpretations.

## Author

**Siddhi Divate**

## License

This project is intended for educational and academic purposes.
