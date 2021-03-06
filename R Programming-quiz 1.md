## WEEK 1 QUIZ
### 1. Question 1
R was developed by statisticians working at

Answer: The University of Auckland  (The R language was developed by Ross Ihaka and Robert Gentleman who were statisticians at the University of Auckland in New Zealand.)

### 2. Question 2
The definition of free software consists of four freedoms (freedoms 0 through 3). Which of the following is NOT one of the freedoms that are part of the definition? Select all that apply.

Answer: The freedom to restrict access to the source code for the software./ The freedom to sell the software for any price./ The freedom to prevent users from using the software for undesirable purposes.

### 3. Question 3
In R the following are all atomic data types EXCEPT: (Select all that apply)

Answer: Table/array/list/data frame /matrix

### 4. Question 4
If I execute the expression x <- 4L in R, what is the class of the object `x' as determined by the `class()' function?

Answer: Integer (The 'L' suffix creates an integer vector as opposed to a numeric vector.)

### 5. Question 5
What is the class of the object defined by x <- c(4, TRUE)?
Answer: numeric

What is the class of the object defined by the expression x <- c(4, "a", TRUE)? 
Answer: Character

### 6. Question 6
If I have two vectors x <- c(1,3, 5) and y <- c(3, 2, 10), what is produced by the expression rbind(x, y)?

Answer: a matrix with two rows and three columns

### 7. Question 7
A key property of vectors in R is that

Answer: elements of a vector all must be of the same class

### 8. Question 8
Suppose I have a list defined as x <- list(2, "a", "b", TRUE). What does x[[1]] give me? Select all that apply.
a numeric vector containing the element 2. / a numeric vector of length 1.

Suppose I have a list defined as x <- list(2, "a", "b", TRUE). What does x[[2]] give me? Select all that apply.
a character vector containing the letter "a". / a character vector of length 1.

### 9. Question 9
Suppose I have a vector x <- 1:4 and a vector y <- 2. What is produced by the expression x + y?

Answer: a numeric vector with elements 3, 4, 5, 6.

### 10. Question 10
Suppose I have a vector x <- c(3, 5, 1, 10, 12, 6) and I want to set all elements of this vector that are less than 6 to be equal to zero. What R code achieves this? Select all that apply.

x[x <= 5] <- 0
Correct 
You can create a logical vector with the expression x <= 5 and then use the [ operator to subset the original vector x.
x[x < 6] <- 0
Correct 
You can create a logical vector with the expression x < 6 and then use the [ operator to subset the original vector x.
x[x %in% 1:5] <- 0
This should be selected 

### 11. Question 11
Use the Week 1 Quiz Data Set to answer questions 11-20.
In the dataset provided for this Quiz, what are the column names of the dataset?

Answer: Ozone, Solar.R, Wind, Temp, Month, Day

### 12. Question 12
Extract the first 2 rows of the data frame and print them to the console. What does the output look like?

Answer:
  Ozone Solar.R Wind Temp Month Day
1    41     190  7.4   67     5   1
2    36     118  8.0   72     5   2

### 13. Question 13
How many observations (i.e. rows) are in this data frame?

Answer: 153  (You can use the `nrows()' function to compute the number of rows in a data frame.)

### 14. Question 14
Extract the last 2 rows of the data frame and print them to the console. What does the output look like?

Answer:
    Ozone Solar.R Wind Temp Month Day
152    18     131  8.0   76     9  29
153    20     223 11.5   68     9  30
Correct 
The `tail()' function is an easy way to extract the last few elements of an R object.

### 15. Question 15
What is the value of Ozone in the 47th row?

Answer: 21

### 16. Question 16
How many missing values are in the Ozone column of this data frame?

Answer: 37 (The `is.na' function can be used to test for missing values.)

###17. Question 17
What is the mean of the Ozone column in this dataset? Exclude missing values (coded as NA) from this calculation.

Answer: 42.1 (The `mean' function can be used to calculate the mean.)

### 18. Question 18
Extract the subset of rows of the data frame where Ozone values are above 31 and Temp values are above 90. What is the mean of Solar.R in this subset?

Answer: 212.8

### 19. Question 19
What is the mean of "Temp" when "Month" is equal to 6?

Answer: 79.1

### 20. Question 20
What was the maximum ozone value in the month of May (i.e. Month is equal to 5)?

Answer: 115

