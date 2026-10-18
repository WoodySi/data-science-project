# World Happiness Report: Is Wealth Enough to Explain Happiness?

## Project Overview

This project explores whether economic wealth alone can explain differences in national happiness levels around the world. Using data from the World Happiness Report, the analysis investigates the relationship between GDP per capita and happiness scores while also examining the influence of social support, freedom, health, generosity, and perceptions of corruption.

The project combines statistical analysis and data visualization to identify patterns, trends, and exceptions among countries with different levels of economic development.

---

## Research Question

To what extent does economic wealth (GDP per capita) explain national happiness, and what other factors contribute to differences in well-being?

---

## Dataset

**Source:** World Happiness Report Dataset

The dataset contains country-level indicators including:

- Happiness Score
- GDP per Capita
- Social Support
- Healthy Life Expectancy
- Freedom to Make Life Choices
- Generosity
- Perceptions of Corruption

The data is publicly available for educational and research purposes.

---

## Methods and Tools

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

### Analytical Methods

1. Data Cleaning and Preparation
2. Correlation and Trend Analysis
3. Linear Regression
4. Residual Analysis
5. Comparative Ranking Analysis
6. Data Visualization

---

## Visualizations Included

### 1. GDP vs Happiness Scatter Plot

A scatter plot with a regression line was used to examine the relationship between GDP per capita and happiness.

**Purpose:**
- Visualize the overall trend.
- Determine whether wealth is associated with happiness.
- Identify countries that deviate from the general pattern.

**Key Finding:**
Countries with higher GDP generally report higher happiness scores, but substantial variation remains among countries with similar wealth levels.

---

### 2. Enhanced Bubble Scatter Plot

Additional encodings were added to the scatter plot:

- Bubble Size = Freedom to Make Life Choices
- Bubble Colour = Social Support

**Purpose:**
- Explore factors beyond income.
- Compare multiple dimensions simultaneously.

**Key Finding:**
Countries with stronger social support and greater freedom often achieve higher happiness scores, even when GDP levels are similar.

---

### 3. Residual Analysis

A residual bar chart highlights countries whose happiness scores differ significantly from values predicted by GDP alone.

**Purpose:**
- Identify positive and negative outliers.
- Examine countries that outperform economic expectations.

**Key Finding:**
Some countries achieve substantially higher happiness levels than predicted by wealth alone, suggesting the influence of social and institutional factors.

---

### 4. Wealthiest Countries Comparison

A comparison of happiness scores among the wealthiest countries.

**Purpose:**
- Investigate whether similar levels of wealth produce similar happiness outcomes.

**Key Finding:**
Even among wealthy nations, happiness varies considerably, indicating that economic prosperity is not the sole determinant of well-being.

---

### 5. Happiness Drivers Heatmap

A standardized heatmap compares multiple well-being indicators across selected countries.

**Variables Included:**
- Happiness Score
- GDP per Capita
- Social Support
- Life Expectancy
- Freedom
- Generosity
- Corruption Perception

**Key Finding:**
The happiest countries tend to perform strongly across multiple dimensions rather than relying solely on economic wealth.

---

## Main Findings

The analysis demonstrates that:

- GDP per capita is positively associated with happiness.
- Wealth provides an important foundation for well-being.
- Economic prosperity alone cannot fully explain happiness differences.
- Social support, freedom, health, and institutional quality are important contributors to national well-being.
- Countries with similar levels of wealth can experience very different happiness outcomes.

---

## Limitation

Several limitations should be considered:

- The analysis uses country-level data and may not reflect individual experiences.
- Regression models simplify complex social relationships.
- Some visualizations may contain overlapping observations.
- Standardized values in the heatmap show relative performance rather than absolute differences.
- Results depend on the quality and availability of reported data.

---

## Repository Structure
