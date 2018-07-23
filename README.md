# renaming_variables_in_r
This simple r code will help you rename your variables all at once

Usage

This function is easy to use,

x represents the data set you are intrested in renaming.

y is the vector of new names 

z is the range that you want to change,say you want to change variable 1 to variable 3 you will simply put 1:3,or even c(7,8,19) to change variables 7,8 and 19

example

We are going to rename the iris data set found in the base r installation.Our code will rename variable 2,4 and 5 and print the first 6 elements for illustration purpoces.

new_iris_data=rename(iris,c("sepwidth","petwidth","specs"),c(2,4,5))

head(new_iris_data)
