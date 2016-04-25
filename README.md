# Getting-and-Cleaning-Data-Course-Project
This code loads the relevant pieces of the Samsung Data into objects in R, then tidies each piece of data and combines them into a single
data frame called "mydata". 
As requested per the project instructions "mydata" only has columns that are measurements on mean and standard deviation of each v
variable.
Lines 85-1306 are a very long way of refining the data from "mydata" into another data frame "finaldf" that has the mean of each column for each
subject and each activity for each subject.
I got very close to writing a for loop to be more efficient for creating "finaldf" but for the sake of submitting on time, I wrote it out the hard way. Any suggestions are more than welcome.

The script will do the following:
1.	Merges the training and the test sets to create one data set.
2.	Extracts only the measurements on the mean and standard deviation for each measurement.
3.	Uses descriptive activity names to name the activities in the data set
4.	Appropriately labels the data set with descriptive variable names.
5.	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

