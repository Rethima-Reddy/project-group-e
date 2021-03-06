# R Studio
- [Demo](https://rethima-reddy.github.io/project-group-e/)
- [Source](https://github.com/Rethima-Reddy/project-group-e)
- [Recording-Alekya](https://use.vg/buOCfh)
- [Demo Video by Rethima](https://app.vidgrid.com/view/dyhyehsxk1fG)
- [Manideep's Demo](https://use.vg/2prQWE)
- [Mahender's video demo link](https://app.vidgrid.com/view/YdPiknIyDAFD)

# Team Members
- Alekya [Profile link](https://github.com/AlekyaPochampally) 
<p>
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/alekya.jpeg" width="100" height="100" />
</p><br>

- Mahender Reddy Surkanti [profile link](https://github.com/Mahender1166)
<p>
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/mahi.jpeg" width="100" height="100" />
</p><br>

- Manideep Chamala [Profile link](https://github.com/manideepchamala) 
<p>
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/mani.jpeg" width="100" height="100" />
</p><br>

- RethimaReddy Polam [Profile link](https://github.com/Rethima-Reddy) 
<p>
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/Rethima.jpeg" width="100" height="100" />
</p><br>

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

# Downloading and installation steps

## Download R 
- To analyse data using R we have to download R and R studio. 
- To download go to the link [https://cran.r-project.org/bin/windows/base/](https://cran.r-project.org/bin/windows/base/) and click on <b> Download R 4.0.0 for Windows (84 megabytes, 32/64 bit)</b> present on top of the screen
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/Screenshot%20(207).png" width="850" height="400" />
</p>
- Then the file named <b> R-4.0.0-win.exe </b> will be downloaded.

## Istallation steps for R
- By double cliking on the file a download window will appear and ask the prefered language to continue. You can click on <b>English</b> and then <b> OK </b> (img2)
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/Screenshot%20(299).png" width="250" height="100" />
</p><br>

- Then an information window will appear. Click on <b> Next</b> (img3)
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/Screenshot%20(300).png" width="500" height="350" />
</p><br>

- You can select the destination loaction where to download the file. I choose to place in default loaction i.e., ```C:\Program Files\```. Then click on <b> Next</b>.
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/Screenshot%20(301).png" width="500" height="350" />
</p><br>

- Then click on <b> Next</b> again.
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/Screenshot%20(303).png" width="500" height="350" />
</p><br>

- Continue the process till the end and click on finish. Then installation process of R is completed.
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/Screenshot%20(308).png" width="500" height="350" />
</p><br>

## Download R Studio
- To download R studio go to the link [https://rstudio.com/products/rstudio/download/#download](https://rstudio.com/products/rstudio/download/#download) and click on download for windows.
- An .exe file will be downloaded.


## Installation steps for R studio
- When we double click on the downloaded file a pop up menu as shown
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/Screenshot%20(309).png" width="500" height="350" />
</p><br>

- When we click on Next, we will be asked to choose the location to install. I prefer it to be in the default location that is C:/Program Files as shown.
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/Screenshot%20(310).png" width="500" height="350" />
</p><br>

- After selectin the loaction, we need to continue and click on next which will show this window.
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/Screenshot%20(311).png" width="500" height="350" />
</p><br>

- After completion of the process, we can see the window as follows. Congratualitions on successful installation..!!
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/Screenshot%20(311).png" width="500" height="350" />
</p><br>

- Congratualitions on successful installation..!!

## R Script File
- Whenever we want to learn a new programming language we will start with printing “Hello world”. In R Scripting language Below i have mentioned a small code snippet to print “Hello world”.−
 ``` 
 # Printing Hello World in R.
myString <- "Hello, World!"

print ( myString)
``` 
- The above lines of code can be saved in a file with .R extension.R is a platform independent language that can be executed with similar commands on both windows and linux.
- For Example, I have saved the file as demo.R.Below is the command to run te Script.

```
$ Rscript demo.R  
```
- The Output generated for the above code is
```
[1] "Hello, World!"
```

## Comments in R:
- We can use "#" for commenting is the same as python.R does not support multi-line comments.
```
# Demo Comment
```

## Data types in R:
### Vectors
- Ordered sequence of homogeneous data can be stored in a vector.
- For Example,Below I have created a color vector with some colors names as character type.
``` 
colors <- c('red','green','yellow')

``` 
- To get the type of the Vector we can utilize class() method.Here I have defined a color vector which contains characters.

```
print(colors)
print(class(colors))
```

- Output for the above code
```
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
- Output to print hte list to console:
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
```
M = matrix( c('a','a','b','c','b','a'), nrow = 2, ncol = 3, byrow = TRUE)
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

### Loops:

#### While loop:
- Syntax for a while loop is given below
```
 while (test_expression) {
   statement
}
```
#### For loop:
- Syntax for a for loop is given below
```
for (value in vector) {
   statements
}
```
# Calculations that can be performed on data sets:

## Calulating Sum from set of data
- To calculate sum of set of numbers we have a function called ```sum()``` that will calculate the sum of data we provided. For example:
```
x<- c(1,3,4,6,4,9)
sum(x)
> 27 
```
## Calculating Mean from set of data
- To calculate mean from a set of data we have function called ```mean()``` that will return the mean of the data set provided. For example:
```
x<- c(1,3,4,6,4,9)
mean(x)
> 4.5 
```
## Calculating Median from set of data
- To calculate median from a set of data we have function called ```median()``` that will return the median of the data set provided. For example:
```
x<- c(1,3,4,6,4,9)
median(x)
> 4.
```
## Calculaing Mode from the set of data
- Their is no pre defined function to get mode from set of data. But we can create a function that can calculate the mode from the data set. The required program is as below:
```
x<- c(1,3,4,6,4,9,1,1,5)
Mode <- function(x){
  ux<- unique(x)
  ux[which.max(tabulate(match(x,ux)))]
}

mostRepeated<-Mode(x)
mostRepeated
> 1
```
- Here the ```unique()``` function finds the unique number from the set of data and ```match()``` function will compare betweeen numbers and ```tabulate()``` will store all the resuts for each unique value from the list and ```max()``` function will picks the element with highest score and will return it. 
- Now when we assign a variable to that function like ```mostRepeated``` from our example the value will be stored in it. Thus we can find the most repeated value from a set of data.

## Sorting data
- To calculate sort from a set of data we have function called ```sort()``` that will return the sort of the data set provided. For example:
```
x<- c(1,3,4,6,4,9)
sort(x)
 > 1 3 4 4 6 9
```
## Drawing a histogram from set of data
- We can pictorially represent the data we have. To present the data in the form of histogram, we can use a predefined function called ```hist()```. For example, to a draw a histogram to a dataset called mtcars which will be downloaded by default during the instalaion process of R Studio) 
```
hist(mtcars$gear, main= "Histogram for gear data in mtcars table")
```
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/histo.png" width="800" height="350" />
</p><br>

- gear is a column in the mtcars table as you can see.
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/data.png" width="800" height="350" />
</p><br>

## Drawing a pie chart from set of data
- We can get a pie chart from the data set we have. We can use a predefined method called ```pie()``` to draw a pie chart. For example:
```
slices <- c(10,9,5,2,4)
lablesArray <- c("Math", "Science", "Computer","Biology","history")
pie(slices,lables = lableArray, main = "Pie Chart to represent interests of students")
```
The result of this is as shown. The ```main``` is the parameter to set a title for a diagram.
(pie chart image)
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/pie.png" width="800" height="350" />
</p><br>

## Drawing a boxPlot from set of data present
- We can draw a box plot using a predefined function called ```boxplot()```. Example is as follows:
```
boxplot(mtcars$mpg~mtcars$vs)
```
- This will plot the miles per hour for a car against its engine as shown.(img)
<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/box.png" width="800" height="350" />
</p><br>


# Data extraction from file (CSV files)
For data extraction form any CSv file there is a function provided in R language.
```
read.csv()
```
There are two ways to read the CSV file.
- From user local machine
    User can check the current working directory my giving getwd() command and then paste the CSV file in that location.

 ```
 data <- read.csv("sampleInput.csv", TRUE, ",")
 ```
 - Direcly form internet without downloading
     User can provide the CSV file URL 

```
data <- read.csv("https://people.sc.fsu.edu/~jburkardt/data/csv/homes.csv",TRUE,",")
```
 Explanation of the above command:
 - data is m y variable and I will be a dataframe. 
 - sampleInput.csv is my input file
 - TRUE is a parameter which will be telling the IDE that my CSV files contains headers for the coulmns
 - "," tells the system, that each tuple is separtaed my a comma. Generally values in CSV files are separated by comma hence the name- comma separated values.

 Now the whole input text is in "data" variable.

 Visualising the data extracted form the CSV files( any column of user choice) in the form of a histogram
 ```
hist(data$age, main="Ages of users", ylab="users", xlab="Ages")
```
Explanation of the above command:
- hist represents histogram
- $age: column user want to shown in histogram
- main: Title for the histogram
- ylab: name of y axis
- xlab: name of x-axis

<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/histogram.png" width="850" height="400" />
</p>

Visualising the data in the form of scatter plots
```
plot(data$age, data$income, ylab="Income", xlab="Age")
```
Explanation of the above command:
- plot represents scatterplot
- $age: column user want to shown in histogram
- $income: column user want to shown in histogram
- ylab: name of y axis
- xlab: name of x-axis

<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/scatterplot.png" width="850" height="400" />
</p>


Visualising the data in the form of boxplot
```
boxplot(data$age)
```
Explanation of the above command:
- boxplot represents scatterplot
- $age: column user want to shown in histogram

<p align="center">
  <img src="https://raw.githubusercontent.com/Rethima-Reddy/project-group-e/master/Images/boxplot.png" width="850" height="400" />
</p>

  

# Knowledge discovered

# References
- [https://www.datamentor.io/r-programming/](https://www.datamentor.io/r-programming/)
- [https://www.tutorialspoint.com/r/r_basic_syntax.htm](https://www.tutorialspoint.com/r/r_basic_syntax.htm)
- [https://www.youtube.com/watch?v=mcYcjH-1giM](https://www.youtube.com/watch?v=mcYcjH-1giM)
- [http://web.cs.ucla.edu/~gulzar/rstudio/basic-tutorial.html](http://web.cs.ucla.edu/~gulzar/rstudio/basic-tutorial.html)
- [https://stackoverflow.com/](https://stackoverflow.com/) for bug fixes
# Contributors
1. Alekya Pochampally[Profile link](https://github.com/AlekyaPochampally)
2. Mahender Reddy Surkanti [profile link](https://github.com/Mahender1166)
3. Manideep Chamala[Profile link](https://github.com/manideepchamala) 
4. RethimaReddy Polam [Profile link](https://github.com/Rethima-Reddy)
# Repository
- [Recorded Demo](https://use.vg/buOCfh)
- [demo](https://rethima-reddy.github.io/project-group-e/)
- [source](https://github.com/Rethima-Reddy/project-group-e)
- [Manideep's Demo](https://use.vg/2prQWE)

