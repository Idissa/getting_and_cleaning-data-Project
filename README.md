

Objective
R script called run_analysis.R.It follows below steps

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive activity names.
Creates a second, independent tidy data set with the average of each variable for each activity and each subject.


Download the data set,put it in a folder on local drive. When file is unzipped there is a folder called a UCI HAR Dataset
Put run_analysis.R in the parent folder of UCI HAR Dataset, set it as the working directory using setwd() function in RStudio.
Run source("run_analysis.R"), it generates a new file tiny_data.txt in the working directory.
Dependencies

dependencies are automatically installed with the help of  run_analysis.R file. It depends on reshape2 and data.table.
