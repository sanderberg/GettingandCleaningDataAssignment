# Getting and Cleaning Data Course Assignment - Wearable Tech

One of the most exciting areas in all of data science right now is wearable computing. 
Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. 

The data linked to in this assignment represent data collected from the accelerometers from the Samsung Galaxy S smartphone. 

This repository contains the following files:
  `README.md` - provides an overview of the dataset and the scripts, and how they are connected
  `Codebook.md` - the codebook describes the data, variables, transformations and cleaning work that occurred on the data
  `run_analysis.R` - the R script that cleaned the raw data and created the tidy dataset
  `tidy_data.txt` - the cleaned data output

# Generating the Tidy Dataset

The `run_analysis.R` script can be used to generate the tidy data. It undergoes the following operations:
  - gets and reads the wearable tech data
  - merges the training and test data to create one dataset
  - Extracts only the measurements on the mean and standard deviation for each measurement
  - Uses descriptive activity names to name the activities in the data set
  - Relabels the data set with descriptive variable names
  - Creates a second, independent tidy dataset with the average of each variable for each activity and each subject in `tidy_data.txt`
