---
title: "Codebook"
author: "Simran Kharbanda"
date: "2024-04-14"
output: html_document
---

# Source Data

 The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:
[Zip file](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)
 
Here are the data for the project:
[Dataset for the project](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)
  
  
# R script 
"run_analysis.R" is a file with R code which performs the following steps:

1. Reading in the files and merging the training and the test sets to create one data set.
2. Extracting only the measurements on the mean and standard deviation for each measurement
3. Using descriptive activity names to name the activities in the data set
4. Appropriately labeling the data set with descriptive variable names
5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject and without names altered.


# About variables:

`x_train`, `y_train`, `x_test`, `y_test`, `subject_train` and `subject_test` contain the data from the downloaded files.
`x_data`, `y_data` and `subject_data` merge the previous datasets to further analysis.
`features` contains the correct names for the `x_data` dataset, which are applied to the column names.