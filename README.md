Getting_and_Cleaning_Data_Project
=========================================

This repository contains work for the course project "Getting and Cleaning data", part of the Data Science specialization.
What follows first are my notes on the original data.

About the data
------------------

The features are unlabeled and can be found in the x_test.txt. 
The activity labels are in the y_test.txt file.
The test subjects are in the subject_test.txt file.

The same holds for the training set.

About the script and the tidy dataset
-------------------------------------
I created a script called run_analysis.R which will merge the test and training sets together.
Please Note: the UCI HAR Dataset must be extracted and set as the working directory

The script does the following:
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

About the Code Book
-------------------
The CodeBook.md file explains the transformations performed and the resulting data and variables.
