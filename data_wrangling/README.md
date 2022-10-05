# Some tricks for data wrangling

I will be using the [Titanic](https://www.kaggle.com/competitions/titanic/data) dataset. You can download it with the following code. We will also need to load **readr** to import the data and **tidyverse** to perform most of this tricks. Some of the specific packages that we will be using are [dplyr](), [tidyr](), [widyr](https://github.com/juliasilge/widyr) **TO BE CONTINUED**

```R
library(readr)
df <- read_csv("https://raw.githubusercontent.com/GuilleDiaz7/Kaggle-Competitions/main/titanic/data/train.csv")
```

#### Perform a double count to know how many times each value appears in a certain variable.

```R
df %>% 
  count(Cabin) %>% 
  count(n)
````
