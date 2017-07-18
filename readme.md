Getting and Cleaning data final project
This folder contains final project for Getting and Cleaning data course on Coursera.org run_analysis.R download dataset which contains measurements of accelerometer and gyroscope using the phone, attached to one of 30 subjects in the study. More can be found here:

In run_analysis.R following steps are performed in order to clean the data:

Download raw data
Read train and test data
Read activity labels
Bind train and test data together
Set feature names
Add subject and activity columns to data set
Subset columns to contain only subject, activity, and mean and std of measurements
Find final data set, with averages of measurements per subject per activity