The description of the data can be found in UCI Machine Learning Repository

  Merge the training and the test sets to create one data set.

After setting the working directory for the files, read into the tables the data located in
features.txt
activity_labels.txt
subject_train.txt
x_train.txt
y_train.txt
subject_test.txt
x_test.txt
y_test.txt
Assign column names and merge to create one data set.

 Extract  measurements on the mean and standard deviation for each measurement.

Create a logical vector that contains TRUE values for the ID, mean and stdev columns and FALSE values for the others. Subset this data to keep only the necessary columns.

  Use descriptive activity names to name the activities in the data set

Merge data subset with the activityType table to include the descriptive activity names

  Appropriately label the data set with descriptive activity names.

Use gsub function to clean up the data labels.

  Create a independent tidy data set with the average of each variable for each activity and each subject.

 We produced only a data set with the average of each variable for each activity and subject
