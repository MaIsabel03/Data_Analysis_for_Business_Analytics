# Data Analysis for Business Analytics

## Project Overview

This project analyzes regional income differences between Western and Eastern Europe using Eurostat 2021 data on regional household adjusted disposable income.

The main research question was:

> Is there a significant difference in average income levels between Western Europe and Eastern Europe?

The analysis was designed to identify whether regional income differences could provide useful insight for business market-entry and product-launch decisions.

## Dataset

The dataset was extracted from the Eurostat Database and focuses on regional household adjusted disposable income.

The analysis includes:

- 156 regional observations
- 78 Western European regions
- 78 Eastern European regions
- 2021 income data
- Regional income levels measured on a per-capita basis

The income variable represents financial resources available to households for consumption, spending, and saving after accounting for taxes and social benefits. :contentReference[oaicite:0]{index=0}

## Analysis Approach

The project included several stages of statistical analysis.

### Data Preparation

The data was cleaned and prepared before statistical testing. Because the income distribution was not normally distributed, a logarithmic transformation was applied to improve the distribution and support the assumptions of the statistical analysis. :contentReference[oaicite:1]{index=1}

### Descriptive Analysis

Descriptive statistics were used to examine the distribution and variability of income levels across the two regions.

The analysis included:

- Mean
- Median
- Mode
- Variance
- Standard deviation
- Range
- Histograms

The distributions showed higher average income levels and greater variability in Western Europe compared with Eastern Europe. :contentReference[oaicite:2]{index=2}

### Hypothesis Testing

A two-sample t-test assuming unequal variances was used to determine whether the difference in average income between Western and Eastern Europe was statistically significant.

The hypotheses were:

- **H₀:** There is no significant difference in average income levels between Western Europe and Eastern Europe.
- **H₁:** There is a significant difference in average income levels between Western Europe and Eastern Europe.

The analysis found a statistically significant difference between the two regions, with Western Europe showing higher average income levels. :contentReference[oaicite:3]{index=3}

### Regression and Correlation Analysis

Regression and correlation analysis were used to further examine the relationship between income and regional classification.

A regional dummy variable was used:

- `0` = Western Europe
- `1` = Eastern Europe

The regression analysis found a negative coefficient for the Eastern Europe dummy, indicating lower average income levels compared with Western Europe. The correlation analysis also showed a statistically significant negative relationship between income and the regional dummy variable. :contentReference[oaicite:4]{index=4}

## Key Findings

The analysis found significant income differences between Western and Eastern Europe.

Western European regions had higher average income levels, while Eastern European income values were generally lower and more tightly clustered. The statistical results supported the conclusion that region was associated with meaningful differences in income levels. :contentReference[oaicite:5]{index=5}

These findings suggest that Western European regions may offer stronger purchasing-power conditions based on the income measure analyzed. However, income is only one factor in a broader market-entry decision. Businesses should also consider market size, costs, competition, demographics, consumer behavior, and other economic factors.

## Limitations

Several limitations were considered when interpreting the results:

- The analysis focused only on Western and Eastern Europe.
- The dataset represents a single year, 2021.
- Regional aggregation can hide differences between individual countries and regions.
- Additional socioeconomic and demographic variables were not included.
- The logarithmic transformation changes how income differences are interpreted. :contentReference[oaicite:6]{index=6}

These limitations mean that the findings should be used as part of a broader market analysis rather than as the sole basis for a business decision.

## Tools Used

- **Microsoft Excel** — data cleaning, preparation, and descriptive analysis
- **Excel Data Analysis ToolPak** — statistical testing
- **JASP** — statistical analysis and visualization
- **Eurostat** — source of the regional income data

## Repository Structure

```text
Data_Analysis_for_Business_Analytics/
│
├── README.md
│
├── Data/
│   └── Original_dataset_both_regions.xlsx
│
├── Analysis/
│   ├── raw data regressison preparation.xlsx
│   └── raw data regression.jasp
│
└── Report/
    └── Comparative_Analysis_Western_Eastern_Europe.pdf
```

## Project Report

The complete analysis, statistical results, visualizations, limitations, conclusions, and supporting analysis are available in the project report:

`Report/Comparative_Analysis_Western_Eastern_Europe.pdf`

## Skills Demonstrated

- Data cleaning and preparation
- Descriptive statistics
- Hypothesis testing
- Two-sample t-tests
- Regression analysis
- Correlation analysis
- Data visualization
- Statistical interpretation
- Business analysis
- Market-entry analysis
- Excel
- JASP

## Project Documentation

The complete project report is available in:

`Report/Comparative_Analysis_Western_Eastern_Europe.pdf`

The report contains the dataset description, research question, data preparation, descriptive statistics, hypothesis testing, regression and correlation analysis, limitations, conclusions, and supporting visualizations.

## Project Context

This project was completed as part of a Data Analysis for Business Analytics course.

The project demonstrates the use of statistical analysis and business analytics techniques to evaluate regional income differences and translate quantitative findings into potential business insights for market-entry and product-launch decisions.
