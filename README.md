Getting and Cleaning Data
Week 3 Course Project
=================

<H2>Introduction</H2>
This repository contains my work for the course project for the Coursera course "Getting and Cleaning data", as part of the Data Science specialization.

<H2>About the raw data</H2>
The features (561 of them) are unlabeled and can be found in the x_test.txt. The activity labels are in the y_test.txt file. The test subjects are in the subject_test.txt file. The same holds for the training set.

<H2>About the script and the tidy dataset</H2>
A script called run_analysis.R will merge the test and training sets together. Prerequisites for this script are as follows:
- the UCI HAR Dataset must be extracted
- the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"
After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity. This tidy dataset will be written to a tab-delimited file called tidy.txt, which can also be found in this repository.

<H2>About the Code Book</H2>
The CodeBook.md file explains the transformations performed and the resulting data and variables.
