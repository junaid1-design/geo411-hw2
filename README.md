Repository name:
Analysis of variance
Overview
This project analyzes whether average annual precipitation differs across three time periods (1940–1967, 1968–1996, 1997–2025) for Buffalo and San Diego using a random sample of 30 years.

Methods
A period variable was created to group years into three categories. ANOVA was used to test differences in means. Kruskal-Wallis and a median chi-square test were performed as non-parametric alternatives. Levene and Kolmogorov-Smirnov tests were conducted to assess assumptions.

Key Findings
For Buffalo, ANOVA (p = 0.02636) and Kruskal-Wallis (p = 0.03095) indicate statistically significant differences across time periods, with Period2 showing the highest mean precipitation. The median test was not significant.
For San Diego, none of the tests were significant, indicating no statistical evidence of differences across periods.

Tools
R, RStudio, read.csv(), lm(), anova(), kruskal.test(), chisq.test(), ks.test()

Reflection
This project demonstrated how parametric and non-parametric tests can produce different p-values depending on assumptions and how statistical significance depends on the type of test used.
