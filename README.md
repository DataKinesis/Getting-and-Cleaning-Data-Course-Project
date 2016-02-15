Getting and Cleaning Data - Course Project

Run_analysis.R does following to clean the data:

1) Load activities and features
2) Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
3) Loads the activity and subject data for each dataset, and merges those columns with the dataset
4) Merges the two datasets
5) Converts the activity and subject columns into factors
7) Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
7) The end result is shown in the file tidy.txt.