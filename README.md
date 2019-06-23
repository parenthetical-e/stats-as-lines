# Statistical tests as linear models - unrankling ranks
Jonas Lindeløv wrote a [nice blog post](https://lindeloev.github.io/tests-as-linear/#3_pearson_and_spearman_correlation) explaining how common statistical tests amount to special cases of linear regression. This is a real neat unfication. His work included examples of nonparametric tests, based on ranks. He seems to dismiss nonparametric tests as not that different from parametric ones. That seemed off to me. But in trying to explain to myself why, I realized my intuition for what ranks do to data was too limited to say anything for sure. So I made some examples here to try and understand ranks better....

# Usage
Open up the `.Rmd` notebook and play! (If you're not familair with [R](https://www.r-project.org/about.html), read the next section.)

# Dependencies
All experiments are done in [Rmarkdown](https://rstudio.com) notebooks, in the [R language](https://www.r-project.org/about.html) using tools from the [tidyverse](https://www.tidyverse.org).

You'll need a recent copy of [R studio](https://rstudio.com), and a R version >3.5.1 (2018-07-02).

## Specific packages
- ggplot2
- tidyr
- dplyr
- broom
- MASS
- gridExtra
- grid
