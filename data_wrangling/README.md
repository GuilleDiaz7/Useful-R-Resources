# Some tricks for data wrangling

I will be using the titanic data. You can download it with the following code. We also load **readr** to import the data and **tidyverse** to perform most of this tricks.

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
