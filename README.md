READ-ME FILE
Dataset Description: 
This dataset is from a 2014 survey that measures attitudes towards mental health and frequency of mental health disorders in the tech workplace. Mental Health Survey (note, there are two sheets in the workbook) which are merged into one for formatting, analysis and visualization.
R Markdown file is being used to perform the data preparation steps including cleaning, analysis and visualization.
Step 1: All R statistical packages and libraries in R Studio were used and downloaded
They are tidyverse, knitr, dplyr, tools, stringr, ggplot2, rlang.
Step 2: Reading the data into R
Using read_csv commands loading the data into data frames.
Also, converting data type of AGE column from number to integer.
Step 3: Merging two data frames into one data frame.
The survey file contains two CSV files which are merged into one data frame for downstream data formatting, handling missing values and visualization.
After merge, there are 1,259 rows X 27 columns.
Step 4: Limiting the data frame to the following columns
This step is to limit the data frame to a subset of columns of interest.
(1) AGE
(2) GENDER
(3) COUNTRY
(4) STATE
(5) FAMILY_HISTORY
(6) TREATMENT
(7) WORK_INTERFERE
(8) NO_EMPLOYEES
(9) REMOTE_WORK
(10) TECH_COMPANY
(11) CARE_OPTIONS
(12) WELLNESS_PROGRAM
(13) LEAVE
(14) COWORKERS
(15) SUPERVISOR
Step 5: Arrange the data in the data frame by STATE
Arranging the data by state in ascending order.
Step 6: Limit the data to include the following
(1) Population of United States 
(2) considering age group above 15 years of age

Step 7: Summary Statistics and finding unique values per column

(1) Determining the summary statistics i.e min, 1st Q, 3rd Q, max
(2) Finding unique values for each column to determine categories for categorical columns 

Step 8: Converting all the column names to upper case including spelling

Converting all the column names to upper case.

Step 9: Formatting the data in the data frames, handling missing values, checking spellings

In the below code we are -

(1) Formatting the data for given columns:
GENDER, FAMILY_HISTORY, TREATMENT, NO_EMPLOYEES, REMOTE_WORK, TECH_COMPANY, CARE_OPTIONS, WELLNESS_PROGRAM, LEAVE, COWORKERS, SUPERVISOR

To transform and standardize the value for easy analysis and application of machine learning algorithms.

(2) Handling missing values
By assigning NA to missing values

Step 10: Create the following visuals

A set of visuals that describe the data and give a clear understanding of statistics.

