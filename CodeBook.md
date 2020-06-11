The run_analysis.R script performs the data preparation followed by the 5 steps required as described in the course project’s definition.

Download and unzip the dataset provided in the project instruction page of the course.

create data frames
features <- features.txt : 561 rows, 2 columns (the features are accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ.)
activities <- activity_labels.txt : 6 rows, 2 columns
subject_test <- test/subject_test.txt : 2947 rows, 1 column
x_test <- test/X_test.txt : 2947 rows, 561 columns
y_test <- test/y_test.txt : 2947 rows, 1 columns
subject_train <- test/subject_train.txt : 7352 rows, 1 column
x_train <- test/X_train.txt : 7352 rows, 561 columns
y_train <- test/y_train.txt : 7352 rows, 1 columns

Merge training and test sets using rbind() and cbind()

Extracts only the mean and standard deviation for each measurement by selecting only subject, code, mean, std from Merged_data

Give descriptive labels to the activities in the data set

 Acc  to Accelerometer
 Gyro to Gyroscope
 BodyBody to Body
 Mag to Magnitude
 character f to Frequency
 character t to Time


Export FinalData into FinalData.txt file.
