# Useful R Resources
A compilation of R resources that helped me. Go to this [link](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) if you want to learn how to style your own README.
The following are books or courses that cover almost everything: [Albert Rapp](https://yards.albert-rapp.de/index.html).

## Setting up yourself
1. A collection of short tutorials on basic R features. I recommend the ones on installing R and RStudio and on how to use R Projects: [link](https://alexd106.github.io/intro2R/howto.html#rstudio_proj-vid)

### RStudio shorcuts
1. Create a new script: **CRTL** + **SHIFT** + **n**
2. Save a script: **CTRL** + **s**
3. Pipe operator %>%: **CTRL** + **SHIFT** + **m**
4. This operator ~: **ALT GR** + **4** + **SPACE**.

## Git and GitHub
1. A wonderful [book](https://happygitwithr.com/index.html) to show how to use Git and GitHub to R users. I followed the first chapters when I started to work with Git.
2. A nice interactive website to learn Git branching: [link](https://learngitbranching.js.org/?locale=es_ES).

## Data Wrangling

### Tidyverse
1. This four-part series on Data Wrangling by RStudio. Recommended even for more advanced R users: [(1) Introduction](https://www.youtube.com/watch?v=jOd65mR1zfw), [(2) Tidy Data and tidyr](https://www.youtube.com/watch?v=1ELALQlO-yM), [(3) Data Manipulation Tools: dplyr](https://www.youtube.com/watch?v=Zc_ufg4uW4U&t=393s) and [(4) Working with Two Datasets](https://www.youtube.com/watch?v=AuBgYDCg1Cg).
2. Some use cases and tricks on **dplyr::filter**: [1](https://sebastiansauer.github.io/dplyr_filter/) and [2](https://blog.exploratory.io/filter-data-with-dplyr-76cf5f1a258e).

### Complementary to tidyverse
1. Function **apply** and derivatives (to avoid loops): [link](https://www.guru99.com/r-apply-sapply-tapply.html)
2. In janitor, the function **tabyl**.

### Advanced Data Wrangling with Tidyverse

#### Common cases
1. How to use **dplyr::across** to perform operations on multiple columns: [documentation](https://dplyr.tidyverse.org/articles/colwise.html#if-_at-_all) and [nice blogpost](https://willhipson.netlify.app/post/dplyr_across/dplyr_across/).
2. Difference between **across** and **c_across**: [link](https://community.rstudio.com/t/when-to-use-c-across-instead-of-across/74582).
3. Create new variables with **case_when** (and **mutate**): [link](https://www.statology.org/conditional-mutating-r/) and a nice [advice](https://stackoverflow.com/questions/39257820/keep-value-if-not-in-case-when-statement) and to solve problems with [UTF-8 characters](https://stackoverflow.com/questions/52007491/how-to-find-french-utf-8-accent-character-in-r-with-the-simple-character-using-s). 

#### Specific cases
1. Fill empty cells with NA (with tidyverse): [Link](https://www.codingprof.com/3-ways-to-replace-blanks-with-nas-in-r-examples/).
2. Add empty columns to a dataframe with **add_column()**: [link](https://www.marsja.se/how-to-add-an-empty-column-to-dataframe-in-r-with-tibble/).

## Data Visualization (with ggplot)

### Theory
1. Some tricks on how to effectively use color: [link](https://albert-rapp.de/posts/ggplot2-tips/07_four_ways_colors_more_efficiently/07_four_ways_colors_more_efficiently.html).

### Basic

### Advanced
1. Multi panel plots with **facet_wrap** and **facet_grid**: [link](http://zevross.com/blog/2019/04/02/easy-multi-panel-plots-in-r-using-facet_wrap-and-facet_grid-from-ggplot2/).

## Web Scraping
1. A thorough and beautiful tutorial, by Andrew Heiss: [link](https://talks.andrewheiss.com/2022-seacen/presentation/#/title-slide)
2. Web scraping with GitHub Actions video tutorial: [link](https://www.youtube.com/watch?v=N3NrWMxeeJQ)

## Statistics

### Regression

#### Linear Regression
1. Though not in R, it is a wonderful explanation of a fundamental method: [link](https://mlu-explain.github.io/linear-regression/).

#### Poisson Regression
2. Poisson regression (not tidymodels): [link](https://www.dataquest.io/blog/tutorial-poisson-regression-in-r/).
3. Zero inflated poisson regression: [link](https://juliasilge.com/blog/rstats-vignettes/).

### Time Series Analysis
1. The R code of Hands on Time Series Analysis with T, chapter by chapter: [link](https://github.com/RamiKrispin/Hands-On-Time-Series-Analysis-with-R).

## RMarkdown
1. Make awesome tables with [kable](https://cran.r-project.org/web/packages/kableExtra/vignettes/awesome_table_in_pdf.pdf).

## Shiny Apps

### Examples
1. An incredible example with U.S. gas prices: [link](https://github.com/kcuilla/USgasprices).
