# School_District_Analysis
## Introduction
This project’s overall goal was to utilize pandas to extract and analyze data from a csv file. In this particular case, the csv file used contained school information such as school name, grade, math and reading score, school type, and school budget. In order to extract and analyze specific sets of data within the csv file the following pandas’ functions were used.
## Pandas functions used
### 1) Pandas data frame
This was used to extract data from the csv file without altering the contents of the csv file itself. 
###2) df.isnull()
Isnull() is a funcation which check for null values within a data frame. This function is typically used for data cleaning.
### 3) df.duplicated() and drop_duplictes()
This function is used to check for and drop duplicates within a data frame.
### 4) df.dtypes
df.dtypes checks each data type in every column of the data frame.
### 5) df.loc()
Searches for a specific column, row, value, combination of all within the data frame.
### 6) df.describe()
Describes the count, mean, std, min, and percentile of a data frame. 
### 7) df.iloc[]
Like loc, this searches for a specific row or column in the data frame using the index.
### 8) df.groupby()
Groups data frame by a specific category within the data frame. 

## Finding in the school district analysis
Via the analysis of testing, grade, and financial data from various different school types, I was able to deduce the following key findings. Primarily, it was found the out of 14831 data points the average student was in 10th grade, and had a mean reading and math score of 72 and 65 respectively. Secondly, it was found that the lowest reading score was from a charter school where the budget is slightly lower than that of a public school. However, lastly, it was found that charter schools have higher overall math scores than that of public schools. 
