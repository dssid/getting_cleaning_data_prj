# Course Project (Getting & Cleaning Data)

## Requirements

You should create one R script called ```run_analysis.R``` that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps

1. Download the data source from <https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip> and save it into a desired target folder on your local drive. Unzipping creates ```/UCI HAR Dataset``` folder with all its associated data.
2. Create ```run_analysis.R``` under the parent folder of ```/UCI HAR Dataset``` and set the target folder as your working directory using the function in RStudio.
3. Running ```source("run_analysis.R")``` will generate ```tiny_data.txt``` file in your working directory.

## Dependencies

```run_analysis.R``` will install the dependencies (```reshape2``` & ```data.table```) automatically if the packages does not exist.
