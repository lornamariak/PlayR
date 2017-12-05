---
title       : Introduction to R Syntax.
description : Simple introduction to R concepts and syntax.Just Like any other Language R has its own variations.Throughout this chapter we shall explore the differences.

  

---
## Inputs in R  

```yaml
type: NormalExercise
lang: r
xp: 50
skills: 1
key: 1a3cc1823e
```

While inputting variables on R we use a special combination of symbols "<"and "-".
The combination of the two <- gives the assignment symbol.
Take an example here
 var <- 56

`@instructions`
 Assign the following variables 20 and Sean 
 to your age(integer) and name (string)

`@hint`
Have a look at this assignment.
name <- "lorna"

`@pre_exercise_code`
```{r}
#not required

```
`@sample_code`
```{r}
#Define 1st variable here

#Define 2nd variable here


`@sct`
```{r}
# SCT written with testwhat: https://github.com/datacamp/testwhat/wiki

test_object ("name")
test_object("age ")
success_msg =("great job")
incorrect-msg =("try using name and age as variable names")



```

