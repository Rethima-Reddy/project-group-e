# R Studio

# Team Members
1. Alekya [Profile link]() 
2. Mahender Reddy Surkanti [profile link](https://github.com/Mahender1166)
3. Manideep [Profile link](https://github.com/manideepchamala) 
4. RethimaReddy Polam [Profile link]() 

# Introduction

## R language
### What is R?
- R is a programming language and environment commonly used in statistical computing, data analytics and scientific research. <br>
- It is one of the most popular languages used by statisticians, data analysts, researchers and marketers to retrieve, clean, analyze, visualize and present data.

## Keypoints on R:
1. R is open-source and free!
1. R is popular – and increasing in popularity
1. R runs on all platforms
1. R is being used by the biggest tech giants

## Basic syntax:
- After setting up the R environment open command promt and type the following
``` $ R
This will launch R interpreter and you will get a prompt > where you can start typing your program as follows −
> myString <- "Hello, World!"
> print ( myString)
[1] "Hello, World!" 
``` 
## R Script File
- Usually, you will do your programming by writing your programs in script files and then you execute those scripts at your command prompt with the help of R interpreter called Rscript. So let's start with writing following code in a text file called test.R as under −
 ``` 
 # My first program in R Programming
myString <- "Hello, World!"

print ( myString)
``` 
- Save the above code in a file test.R and execute it at Linux command prompt as given below. Even if you are using Windows or other system, syntax will remain same.
``` $ Rscript test.R  
```

## Comments in R:
- “#” is used for commenting. R dosent no support multi line comment.
```
# this is my comment.
```

## Data types in R:
### Vectors
``` 
Eg: colors <- c('red','green',"yellow")
- print(colors)
``` 

#### Get the class of the vector.
```
print(class(colors))

o/p:
 [1] "red"    "green"  "yellow"
[1] "character"
```
### 	Lists
- Create a list.
```
list1 <- list(c(2,5,3),21.3,sin)
```

-  Print the list.
```
print(list1)
```
- o/p:
``` [[1]]
[1] 2 5 3

[[2]]
[1] 21.3

[[3]]
function (x)  .Primitive("sin")
```
### Matrices
1.  Eg: A matrix is a two-dimensional rectangular data set. It can be created using a vector input to the matrix function.

-  Create a matrix.
``` M = matrix( c('a','a','b','c','b','a'), nrow = 2, ncol = 3, byrow = TRUE)
print(M)
```
- When we execute the above code, it produces the following result −
```   
[,1] [,2] [,3]
[1,] "a"  "a"  "b" 
[2,] "c"  "b"  "a"
```

### Arrays
1. Eg: # Create an array.
``` 
a <- array(c('green','yellow'),dim = c(3,3,2))
print(a)
```
- When we execute the above code, it produces the following result −
``` 
, , 1

     [,1]     [,2]     [,3]    
[1,] "green"  "yellow" "green" 
[2,] "yellow" "green"  "yellow"
[3,] "green"  "yellow" "green" 

, , 2

     [,1]     [,2]     [,3]    
[1,] "yellow" "green"  "yellow"
[2,] "green"  "yellow" "green" 
[3,] "yellow" "green"  "yellow"  
```
### Factors
```
Create a vector.
apple_colors <- c('green','green','yellow','red','red','red','green')

# Create a factor object.
factor_apple <- factor(apple_colors)

# Print the factor.
print(factor_apple)
print(nlevels(factor_apple))
```
- When we execute the above code, it produces the following result −
```
[1] green  green  yellow red    red    red    green 
Levels: green red yellow
[1] 3
```

### Data Frames
1. Data Frames are created using the data.frame() function.
#### Create the data frame.
```
BMI <- 	data.frame(
   gender = c("Male", "Male","Female"), 
   height = c(152, 171.5, 165), 
   weight = c(81,93, 78),
   Age = c(42,38,26)
)
print(BMI)
```
- When we execute the above code, it produces the following result −
```
  gender height weight Age
1   Male  152.0     81  42
2   Male  171.5     93  38
3  Female  165.0     78  26  
```

### Variable in R:
1.  A valid variable name consists of letters, numbers and the dot or underline characters.
 - Deleting Variable:
1. Variables can be deleted by using the rm() function. Below we delete the variable var.3. On printing the value of the variable error is thrown.
```
Live Demo
rm(var.3)
print(var.3).
```
## Operators:
- Some of the operators can be :
```
1. Arithmetic Operators: +, -, *, /, %%, %/%, ^
2. Relational Operators: <, >, ==, <=, >=, !=
3. Logical Operators: &, |, !, &&,  ||
4. Assignment Operators: Left assignment : <- or == or <<- 
                        Right Assignment: -> or ->>
   ```
## Decision Making:  
if statement <br>
if else statements <br>
switch statements <br>

#### Loops:
```
 Repeat loop 	
       repeat { 
   commands 
   if(condition) {
      break
   }
}
```
#### While loop:
```
 while (test_expression) {
   statement
}
```
#### For loop:
```
for (value in vector) {
   statements
}
```













# Downloading procedure

# Basic syntax and data structures in R language

# Data extraction from file (CSV files)

# Knowledge discovered

# Refrences
[Reference Link](https://www.datamentor.io/r-programming/)

# Contributors
1. Alekya [Profile link]() 
2. Mahender Reddy Surkanti [profile link](https://github.com/Mahender1166)
3. Manideep [Profile link](https://github.com/manideepchamala) 
4. RethimaReddy Polam [Profile link]()
