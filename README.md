# Heart Disease Statistical Analysis in R

## Project Overview

This project explores a heart disease dataset using R and statistical techniques. The aim was to understand the relationships between age, maximum heart rate, resting blood pressure and cholesterol. The analysis uses descriptive statistics, correlation analysis, scatter plots and linear regression to identify patterns and relationships within the dataset.

The dataset contains **1,025 observations and 14 variables**.

## Tools and Technologies

- R
- RStudio
- R Markdown
- Statistical Analysis
- Data Visualisation

## Analysis Performed

The project involved:

- Exploring the dataset using `head()`, `str()` and `summary()`.
- Calculating descriptive statistics.
- Creating scatter plots to examine relationships between variables.
- Using Pearson correlation to measure the strength and direction of relationships.
- Applying linear regression to examine relationships between selected variables.
- Creating a boxplot to compare maximum heart rate between sex groups.

## Key Findings and Results

### 1. Age vs Maximum Heart Rate

**Correlation coefficient: -0.3902**

The analysis identified a moderate negative relationship between age and maximum heart rate.

The scatter plot shows a general downward pattern, suggesting that older individuals in the dataset tend to have lower maximum heart rate values.

The correlation is statistically significant (p < 0.001).

### 2. Age vs Resting Blood Pressure

**Correlation coefficient: 0.2711**

The results show a weak positive relationship between age and resting blood pressure.

The scatter plot indicates a slight upward trend, suggesting that resting blood pressure tends to increase with age in this dataset. However, the relationship is relatively weak.

The correlation is statistically significant (p < 0.001).

### 3. Age vs Cholesterol

**Correlation coefficient: 0.2198**

The analysis shows a weak positive relationship between age and cholesterol levels.

The scatter plot suggests a slight upward pattern, although the points are widely spread. This indicates that age alone does not strongly explain differences in cholesterol levels.

The correlation is statistically significant (p < 0.001).


## Visualisations

### Age vs Maximum Heart Rate

![Age vs Maximum Heart Rate](images/age_max_heart_rate.png)

The downward pattern illustrates the negative relationship between age and maximum heart rate.

### Age vs Resting Blood Pressure

![Age vs Resting Blood Pressure](images/age_resting_blood_pressure.png)

The slight upward pattern illustrates the weak positive relationship between age and resting blood pressure.

### Age vs Cholesterol

![Age vs Cholesterol](images/age_cholesterol.png)

The scatter plot shows a weak positive relationship between age and cholesterol, with considerable variation between observations.

## Conclusion

The analysis identified different relationships between age and three health-related measurements. The strongest relationship was between age and maximum heart rate, which showed a moderate negative correlation. Resting blood pressure and cholesterol both showed weak positive correlations with age. Although the correlation tests were statistically significant, the regression results showed that these variables alone explained only a limited proportion of the variation.

Overall, this project demonstrates the use of R for data exploration, statistical analysis, correlation, linear regression and data visualisation.

## Dataset

The dataset was obtained from Kaggle:

[Heart Disease Dataset – Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

## Project Files

- `heart_disease_analysis_markdown.Rmd` – R Markdown source code containing the analysis.
- `images/` – Folder containing the scatter plot visualisations and boxplot.

