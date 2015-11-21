##About
 
This script merges the training and the test sets to create one data set and extracts only the measurements
on the mean and standard deviation for each measurement in the combined dataset. It names the feature columns
1 using labels in the features_info.txt file and creates two additional columns, one for subject and the other
for activity. The subject and activity columns are also combined from test and train sets in the same order as features.
Further, activity column numbers are converted to descriptive names using the mapping present in activity_label.txt.
Finally, data is summarized by combining mean of each feature for each subject and activity. This summary is written
to a file and is also printed.

##Dependencies
 
User must have dplyr package installed to run this script
 
##Running the Script
 
Script should be run from the same working directory where the data is present, specifically, at the same level
as “UCI HAR Dataset” directory. The script can be executed by typing the following command on the R command line prompt:
 
**source(run_alalysis.R)

 
##Output
 
Upon completion, the script prints the summary data and also writes it to the file called “mydata.txt” in the same directory.