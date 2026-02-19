Analysis of Variance – Geography 411 Homework 2
Overview
This project analyzes annual precipitation data for Buffalo and San Diego. The goal is to determine whether precipitation differs significantly across three time periods.
The data were divided into:
Period 1: Year ≤ 1967
Period 2: 1967 < Year < 1997
Period 3: Year ≥ 1997
Statistical tests were performed to evaluate differences among periods.
Methods
The following statistical methods were used:
Kolmogorov-Smirnov (KS) test to check normality
One-way ANOVA to compare means
Kruskal-Wallis test as a non-parametric alternative
Median test using chi-square
Boxplots and histograms for visualization
All analyses were conducted in R.
Key Findings
For Buffalo:
ANOVA showed a significant difference among periods (p < 0.05).
Kruskal-Wallis test also indicated significant differences.
For San Diego:
ANOVA showed no significant difference among periods (p > 0.05).
Kruskal-Wallis test confirmed no significant difference.
This suggests that precipitation patterns changed over time in Buffalo but remained relatively stable in San Diego.
Tools
RStudio
R statistical software
GitHub for version control
Reflection
This assignment helped me understand how to compare multiple groups using both parametric and non-parametric methods. I learned how to test assumptions such as normality and how to interpret statistical results using p-values. Using GitHub improved my ability to organize and document analytical work.
