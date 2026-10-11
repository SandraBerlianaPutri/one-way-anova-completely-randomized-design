# One-Way ANOVA: Completely Randomized Design

## About
This project applies a General Linear Model and one-way ANOVA under a Completely Randomized Design (CRD) to compare chlorophyll content among cassava, spinach, and lettuce leaves.

## Project Analysis
[**View Full Analysis on RPubs**](https://rpubs.com/sandraberlianaputri/one-way-anova-matrix-chlorophyll)

## Dataset

The dataset contains chlorophyll content measurements from three types of plant leaves, with three observations for each type (9 observations in total).

| Plant Type | Observation 1 | Observation 2 | Observation 3 |
|---|---:|---:|---:|
| Cassava | 18.50 | 17.70 | 18.00 |
| Spinach | 10.70 | 11.20 | 11.20 |
| Lettuce | 1.60 | 2.00 | 1.89 |

**Variables**
- **Response variable:** Chlorophyll content
- **Treatment factor:** Plant type (cassava, spinach, and lettuce)
- **Experimental design:** Completely Randomized Design (CRD), with three replicates per treatment

## Methods
- **General Linear Model:** Model matrix construction, \(X'X\) and \(X'y\) calculations, and parameter estimation.
- **ANOVA:** Testing differences in mean chlorophyll content across three plant types.
- **Assumption Testing:** Shapiro–Wilk test for residual normality and Bartlett's and Levene's tests for variance homogeneity.
- **Model Evaluation:** F-test to assess treatment effects.

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University.
