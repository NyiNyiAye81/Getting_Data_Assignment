#CodeBook

This file explains the required input and expected output when running the run_analysis.R script.

Here is the data used in this analysis:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

After unzipping the data, we have a folder called UCI HAR Dataset and we will only need the following files:

features.txt, activity_labels.txt, train/subject_train.txt,train/X_train.txt, train/y_train.txt,test/subject_test.txt,
test/X_test.txt ,test/y_test.txt


Activity Label
 
  WALKING (value 1): subject was walking during the test
  
  WALKING_UPSTAIRS (value 2): subject was walking up a staircase during the test
  
  WALKING_DOWNSTAIRS (value 3): subject was walking down a staircase during the test
  
  SITTING (value 4):subject was sitting during the test
  
  STANDING (value 5): subject was standing during the test
  
  LAYING (value 6): subject was laying down during the test

subject - The ID of the test subject.

activity - The type of activity performed when the corresponding measurements were taken

The result is written into [tidy_data.txt](https://github.com/NyiNyiAye81/Getting_Data_Assignment/blob/master/tidy_data.txt).
