GettingAndCleaningDataCoursera
=============================

The current file describes the steps needed to run the run_analysys.R file.

* Download the file from this link: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
* Unzip the file and change the folder name to "project".
* Set the working directory in which run_analysis.R is saved.
* Run source("run_analysis.R") in R.
* There are 2 output files generated: "tidy_data_set.txt" (contains the first tidy data set for mean and std columns) and "means_tidy.txt" (contains the second tidy data set with the average of each variable grouped by "subject" and "activity").
* Both files will be generated in your actual working directory.
* Run read.table("tidy_data_set.txt") and read.table("means_tidy.txt").
