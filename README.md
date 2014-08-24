Getting and Cleaning Data Coursera Project
===========================================

This repository contains my work for the course project for the Coursera course "Getting and Cleaning data", part of the Data Science specialization. 

The files in this repo are describe in the following sections.

run_analysis.R (the script)
---------------------------------
First of all, I'm going to describe the raw data. The features (561 of them) are unlabeled and can be found in the x_test.txt .The activity labels are in the y_test.txt file. The test subjects are in the subject_test.txt file. Idem for the training set.

I created a script called run_analysis.R which will merge the test and training sets together.This script requires the UCI HAR Dataset must be extracted and the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset".
After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Finally, the script will create a tidy data set containing the means of all the columns per test subject and per activity. 

The tidy.txt dataset
---------------------

This tidy dataset will be written to a tab-delimited file called tidy.txt, which can also be found in this repository.

Code Book.md
---------------
The CodeBook.md file describes the variables, the data, and any transformations or work that I performed to clean up the data.
