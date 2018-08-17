# getting-and-cleaning-data-course-project
This is the course project for the Getting and Cleaning Data Cousera course. The R script, run_analysis.R, does the following:

Downloads abd unzips the dataset if it does not already exist in the working directory.
Loads the activity and feature information
Loads both the training and test datasets, keeping only the columns which reflect the mean or standard deviation for each measurement.
Loads the activity and subject data for each dataset, and merges those columns with the dataset
Merges the two (training and test) data sets
Converts the activity and subject columns into factors
Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
The end result is shown in the file tidy.txt. 
