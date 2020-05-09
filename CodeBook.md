## CODE BOOK - Getting and Cleaning dataset

# Downloading dataset

The data of UCI HAR dataset was downloaded from the Url https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
 and then the folder was unzipped.
 
 The original dataset was trasnformed by :
 
1. Merging the training and the test sets to create one data set.
2. Extracting only the measurements on the mean and standard deviation for each measurement.
3. Using descriptive activity names to name the activities in the data set
4. Appropriately labeling the data set with descriptive activity names.
6. Creating a second, independent tidy data set with the average of each variable for each activity and each subject.

## R Script

File with name run_analysis.R has the R codes for the above mentioned dataset.
Tidy.text named file contains the cleaned dataset.

## Variables Description

1. subject - The ID of the test subject
2. activity - The type of activity performed when the corresponding measurements were taken

## Activity Labels

* WALKING (value 1): subject was walking during the test
* WALKING_UPSTAIRS (value 2): subject was walking up a staircase during the test
* WALKING_DOWNSTAIRS (value 3): subject was walking down a staircase during the test
* SITTING (value 4): subject was sitting during the test
* STANDING (value 5): subject was standing during the test
* LAYING (value 6): subject was laying down during the test