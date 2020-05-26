# R Studio

# Team Members
1. Alekya [Profile link]() 
2. Mahender Reddy Surkanti [profile link](https://github.com/Mahender1166)
3. Manideep [Profile link]() 
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

## Get the class of the vector.
```
print(class(colors))

o/p:
 [1] "red"    "green"  "yellow"
[1] "character"
```
## 	Lists
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
- Matrices
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

- Arrays
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







# Downloading procedure

# Basic syntax and data structures in R language

# Data extraction from file (CSV files)

# Knowledge discovered

# Rerences

# Contributors
1. Alekya [Profile link]() 
2. Mahender Reddy Surkanti [profile link](https://github.com/Mahender1166)
3. Manideep [Profile link]() 
4. RethimaReddy Polam [Profile link]()
