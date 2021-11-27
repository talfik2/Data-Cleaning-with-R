 Data-Cleaning-with-R
 
 In this repository, I cleaned NYPD Shooting Incident Data with R in this adress: "https://data.cityofnewyork.us/api/views/833y-fsy8/rows.csv?accessType=DOWNLOAD"
 
 This data covers the shooting incidents between 2006 - 2020.
 
 I used Tidyverse packages of R during the Data Cleaning.
 You can find the visualization of this work by selecting 2nd branch of this repository.
 
The functions that I used and their explanations are above:

head() = First 6 rows of DataFrame

Summary() = Summary statistical values of DataFrame

nrow() = Number of rows in DataFrame

ncol() = Number of columns in DataFrame

gather() = Gather takes multiple columns and collapses into key-value pairs, duplicating all other columns as needed.

mutate() = Creating a new column in DataFrame

seperate() = Splitting values by character

str() = types of values in DataFrame

gsub() =  To replace all the matches of a pattern from a string.

str_sub() = Splits the values in the column, and existing column to create new column(s)

replace() = adds or removes column(s).

arrange() = Orders the rows of a data frame by the values of selected columns.

relocate() = Changes the column(s) positions.
