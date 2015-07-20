# Getting and Cleaning Data
This is a repository for any and all code written for the Getting and Cleaning Data Coursera course through Johns Hopkins University. This repository explains how all of the scripts work and how they are connected. 

# Course Project

Find all project-related materials in the UCI HAR Dataset directory. However, copies of the important files have been put into this main directory to fulfill the submission requirement.

1. Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive, for example C:\Users\yourname\Documents\R\

2. Save run_analysis.R into C:\Users\yourname\Documents\R\UCI HAR Dataset\

3. In RStudio, setwd("C:\\Users\\yourname\\Documents\\R\\UCI HAR Dataset\\") and double confirm it: source("run_analysis.R")

4. Use data <- read.table("data_set_with_the_averages.txt") to read the data. 


It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. Note that the provided R script has no assumptions on numbers of records, only on locations of files.
