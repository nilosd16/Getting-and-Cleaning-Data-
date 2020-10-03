# Code book
This is the code book for tidy_data_set which is given.

## Variables Description
Data read from project data files. For description of each data files, refer to README in the project folder.

1.feature_list - features.txt file

2.activity - activity_labels.txt file

3.subject_test - subject_test.txt file

4.x_test - X_test.txt

5.y_test - Y_test.txt

6.subject_train - subject_train.txt

7.x_train - train/X_train.txt

8.y_train -train/Y_train.txt

### Processing variables

1.y_test_label - match y_test labels with corresponding activities

2.tidy_test - binding test subject, test activity and test set

3.y_train_label - match y_train labels with corresponding 
activities

4.tidy_train - binding train subject, train activity and train set

5.tidy_set - merged test set and train set

6.tidy_mean_std - data set with only measurements on the mean and standard deviation for each measurement

7.tidy_avg - independent tidy data set with the average of each variable for each activity and each subject. 
