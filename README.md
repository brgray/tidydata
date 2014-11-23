tidydata
========
#Project for Getting and Cleaning Data, Coursera.

The course instructions were the following:

 1. You should create one R script called run_analysis.R that does the following. 
 2. Merges the training and the test sets to create one data set.
 3. Extracts only the measurements on the mean and standard deviation for each measurement. 
 4. Uses descriptive activity names to name the activities in the data set
 5. Appropriately labels the data set with descriptive activity names. 
 6. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

This Github repository provides a script (*run_analysis.R*) and a codebook (*CodeBook.md*). 

## run_analysis.R

The script performs the following high-level tasks:

- Prepares the R dependencies and the working directories
- Downloads and unzip the original dataset (if not already present)
- Loads the features, keeps only the variable related to mean and std
- Loads the subjects and activities. It merges them.
- It merges features, subjects, and activities
- Cleans the variable names to human readable form (and R coding standard compliant)
- Creates the tiny data set with the average of each variable for each activity and each subject. 

Please note that the steps are documented at a deeper level in CodeBook.md.

## CodeBook.md

The CodeBook contains a description of the original dataset, the data acquisition process, the data transformation process, the variables, and the tidy dataset format.
