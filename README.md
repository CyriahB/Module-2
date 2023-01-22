# Module-2
Introduction to basic R functions and Data Structures - assignment
> assignment2 <- c(16, 18, 14, 22, 27, 17, 19, 17, 17, 22, 20, 22)

> #Evaluate the function 'myMean"

> myMean <- function(assignment2)

+ {

+   return(sum(assignment2)/length(assignment2))

+ }

> myMean(assignment2)

[1] 19.25

Explanation: 

This function works because the definition of mean is the average of the numbers in a dataset. To find the mean of a dataset, we have to find the sum of all of the given values and divide it by the total amount of those values. So to complete the function, we have to ask R to return the sum/length to find the mean of assignment 2, which is exactly what return(sum(assignment2)/length(assignment2)) does.
