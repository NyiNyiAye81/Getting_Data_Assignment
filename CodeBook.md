#CodeBook

This file explains the required input and expected output when running the run_analysis.R script.

Notice: The dataset and input, output are in the same R working environment.

##Input

Here is the data used in this analysis:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

After unzipping the data, we have a folder called UCI HAR Dataset and we will only need the following files:

features.txt, activity_labels.txt, train/subject_train.txt,train/X_train.txt, train/y_train.txt,test/subject_test.txt,
test/X_test.txt ,test/y_test.txt

##Output

The required tidy dataset tidy_data.txt is generated, with the average of each variable for each activity and each subject.

##Variables

The variables in the tidy dataset include:

-activityName: contain the activity names.

Activity ID | Activity Name
  ------------|--------------
  1 | WALKING (value 1): subject was walking during the test
  2 | WALKING_UPSTAIRS (value 2): subject was walking up a staircase during the test
  3 | WALKING_DOWNSTAIRS (value 3): subject was walking down a staircase during the test
  4 | SITTING (value 4):subject was sitting during the test
  5 | STANDING (value 5): subject was standing during the test
  6 | LAYING (value 6): subject was laying down during the test

subject - The ID of the test subject.

activity - The type of activity performed when the corresponding measurements were taken

The result is written into [tidy_data.txt](https://github.com/NyiNyiAye81/Getting_Data_Assignment/blob/master/tidy_data.txt).
