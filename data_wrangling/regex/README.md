# The most common regex cases
I will try to show examples using both **base R** and the function from the **stringr package**.

## Basic operators
### Match-zero-or-more: *
It takes the smallest preceding regular expression and it matches it zero or more times.

### Match-any-character operator: .
It matches any character but newlines or null.

### Match-one-or-more operator: +
Like the . operator but matching at least one character.

### Specific cases
#### Extract a rank
Imagine you have a list like this:
1. Leo Messi.
2. Cristiano Ronaldo
3. Karim Benzema
4. Mohamed Salah
...

12. Kevin de Bruyne
and you want to remove the numbers and keep the names.

```{r}
str_remove(list, pattern = "\\d*.\\s")
```
