# Useful R Resources
A compilation of R resources that helped me. Go to this [link](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) if you want to learn how to style your own README.
The following are books or courses that cover almost everything: (1) [Advanced R](https://adv-r.hadley.nz/), (2) [Albert Rapp](https://yards.albert-rapp.de/index.html).

## Setting up yourself
1. A collection of short tutorials on basic R features. I recommend the ones on installing R and RStudio and on how to use R Projects: [link](https://alexd106.github.io/intro2R/howto.html#rstudio_proj-vid)

### RStudio shorcuts
1. Create a new script: **CRTL** + **SHIFT** + **n**
2. Save a script: **CTRL** + **s**
3. Pipe operator %>%: **CTRL** + **SHIFT** + **m**
4. This operator ~: **ALT GR** + **4** + **SPACE**.

## Git and GitHub
1. A wonderful [book](https://happygitwithr.com/index.html) to show how to use Git and GitHub to R users. I followed the first chapters when I started to work with Git.
2. A video tutorial to get started with Git and GitHub in RStudio: [link](https://www.youtube.com/watch?v=jN6tvgt3GK8).
3. A nice interactive website to learn Git branching: [link](https://learngitbranching.js.org/?locale=es_ES).

## Data Wrangling

### Tidyverse
1. This four-part series on Data Wrangling by RStudio. Recommended even for more advanced R users: [(1) Introduction](https://www.youtube.com/watch?v=jOd65mR1zfw), [(2) Tidy Data and tidyr](https://www.youtube.com/watch?v=1ELALQlO-yM), [(3) Data Manipulation Tools: dplyr](https://www.youtube.com/watch?v=Zc_ufg4uW4U&t=393s) and [(4) Working with Two Datasets](https://www.youtube.com/watch?v=AuBgYDCg1Cg).
2. Some use cases and tricks on **dplyr::filter**: [1](https://sebastiansauer.github.io/dplyr_filter/) and [2](https://blog.exploratory.io/filter-data-with-dplyr-76cf5f1a258e).
3. Ten tricks in the tidyverse: [video](https://www.youtube.com/watch?v=NDHSBUN_rVU).

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
2. A bunch of graphics with some data wrangling tricks: [link](https://www.brodrigues.co/blog/2020-04-12-basic_ggplot2/).

### Tables

#### gt package

1. Various links from RStudio Youtube channel with live coding battles: [1](https://www.youtube.com/watch?v=-c_PUee8Cu0), [2](youtube.com/watch?v=sRxdutTgyDE), [3](https://www.youtube.com/watch?v=tIB_N0nUfNs).
2. New features of the **gt** package: [link](https://www.youtube.com/watch?v=F5TV9uWCJps).

## Web Scraping
1. A thorough and beautiful tutorial, by Andrew Heiss: [link](https://talks.andrewheiss.com/2022-seacen/presentation/#/title-slide)
2. Web scraping with GitHub Actions video tutorial: [link](https://www.youtube.com/watch?v=N3NrWMxeeJQ)

## RMarkdown & Quarto

### RMarkdown
The starting point to RMarkdown: [book](https://bookdown.org/yihui/rmarkdown/).

#### Parametrized reports
1. A nice video tutorial focused on the **params** option: [video](https://www.youtube.com/watch?v=oFKb8WYDLB0&t=613s).
2. This [video](https://www.youtube.com/watch?v=DkQEpqySylc) covers a lot more options to make parametrized reports.

#### Styling
1. Make awesome tables with [kable](https://cran.r-project.org/web/packages/kableExtra/vignettes/awesome_table_in_pdf.pdf).

### Quarto
1. Some slides by a prominent RStudio worker: [link](https://thomasmock.quarto.pub/reports-presentations/#/title-slide).

## Shiny Apps

### Examples
1. An incredible example with U.S. gas prices: [link](https://github.com/kcuilla/USgasprices).

## Other interesting videos
1. The creator of tidyverse showing an example of a data science project: [video](https://www.youtube.com/watch?v=go5Au01Jrvs).
