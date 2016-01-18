# FinalAssignment_GettingAndCleaningData
Coursera Getting and Cleaning Data: Final Project

This assignment reformats the Human Activity Recognition Using Smartphones Data Set.
The source data is available at 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones#
The dataset is also included in the UCI HAR Dataset directory in this repo.

Provided is an R script called run_analysis.R that creates a tidy data set as follows:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of 
each variable for each activity and each subject.

codebook.md defines the variables, values, and units in the tidy data set.

The tidy data in tidy_data_set.txt can be read into R with the following code:
read.table("tidy_data_set.txt", header=TRUE, colClasses=c('factor', 'factor', rep('numeric', 66)))

The tidy_data_set.txt file in this directory is a tidy subset of the data provided in the
tidy_data_set.txt includes the combined test and training data sets from the following files:
UCI HAR Dataset/test/subject_test.txt
UCI HAR Dataset/test/X_test.txt
UCI HAR Dataset/test/y_test.txt
UCI HAR Dataset/train/subject_train.txt
UCI HAR Dataset/train/X_train.txt
UCI HAR Dataset/train/y_train.txt

Note the final tidy data set is 180 rows x 68 columns.
Each column represents a variable or measure or characteristic.
Each variable is in one column.
Each observation of the variable is in a different row.

Details: run_analysis.R
run_analysis.R takes source data from the UCI Har Dataset directory, imports it into R, and 
transforms it into a tidy data subset.
The script performs operations to import, clean, and transform the data set.
The steps are indicated in comments throughout the .R file.

The script assumes the data source files are in the a directory called UCI HAR Dataset in the
current working directory.
The script assumes the directory structure and file names and locations with UCI Har Dataset 
have not been changed since they were extracted from the source .zip file.
References to file locations in run_analysis.R work with the Windows file system.
