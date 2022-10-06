# Some tricks for data wrangling

I will be using the [Titanic](https://www.kaggle.com/competitions/titanic/data) dataset. You can download it with the following code. We will also need to load **readr** to import the data and **tidyverse** to perform most of this tricks. Some of the specific packages that we will be using are [dplyr](), [tidyr](), [widyr](https://github.com/juliasilge/widyr) **TO BE CONTINUED**

```R
library(readr)
df <- read_csv("https://raw.githubusercontent.com/GuilleDiaz7/Kaggle-Competitions/main/titanic/data/train.csv")
```

#### Count NAs across every column

```R
df %>% 
  summarise(across(everything(), ~sum(is.na(.))))
  
# Or, with the purrr package

df %>% 
  purrr:map_df(~sum(is.na(.)))
```

#### The additional options in count: sort, wt and name

```R

```

#### Perform a double count to know how many times each value appears in a certain variable.

```R
df %>% 
  count(Cabin) %>% 
  count(n)
````

#### Count and percentage

```R
df %>%
  group_by(**variable_name**) %>% 
  summarise(n = n()) %>% 
  mutate(Perc = n / sum(n)) %>% 
```
