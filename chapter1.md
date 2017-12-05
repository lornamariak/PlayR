---
title       : The R Syntax.
description : Simple introduction to R concepts and syntax.Just Like any other Language R has its own variations.Throughout this chapter we shall explore the differences.

  

---
##  Variable Assignment in R  

```yaml
type: NormalExercise
lang: r
xp: 50
skills: 1
key: 1a3cc1823e
```

While inputting variables on R we use a special combination of symbols "<"and "-".
The combination of the two gives the assignment symbol "<-".
Take an example here:
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


---
## Comments in R

```yaml
type:NormalExercise
key: 74c7ef01f4
lang: r
xp: 100
skills: 1
```
More about R syntax takes us to commenting code.
Unlike other languages R doesnt support multi line comments.
we use # to set a comment ,however ## is also valid.
any word preceeded by # is executed as a comment
For example 
name <- "sean" #this is just a name

`@instructions`
Comment the code in the script with the following comments
1.This is a string
2.This is an integer


`@hint`
- Use # or ##
- Make sure that the comment comes after #


`@sample_code`
```{r}
# comment the line below
 name <- "hayes"
 
 #comment the line below
 age <- 23
```

