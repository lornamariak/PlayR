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

While inputing variables on R we use a special combination of symbols "<"and "-".
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

---
## Comments in R

```yaml
type: NormalExercise
lang: r
xp: 100
skills: 1
key: 2b3674ebf3
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


`@pre_exercise_code`
```{r}
# You can also prepare your dataset in a specific way in the pre exercise code
load(url("https://s3.amazonaws.com/assets.datacamp.com/course/teach/movies.RData"))
movie_selection <- Movies[Movies$Genre %in% c("action", "animated", "comedy"), c("Genre", "Rating", "Run")]

# Clean up the environment
rm(Movies)
```

`@sample_code`
```{r}
# comment the line below 
name <- "Sean"

# Comment the line below
age <- 89

```

`@solution`
```{r}

```

`@sct`
```{r}

```
