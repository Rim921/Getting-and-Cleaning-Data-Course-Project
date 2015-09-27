#CodeBook.md


• x_train ,  y_train ,  x_test ,  y_test ,  subject_train  and  subject_test  contain the data from the downloaded files.

• x_data ,  y_data  and  subject_data  merge the previous datasets to further analysis.

• A similar approach is taken with activity names through the  activities  variable.

• All_data  merges  x_data ,  y_data  and  subject_data  in a big dataset.

• Finally,  averages_data  contains the relevant averages which will be later stored in a  .txt  file.  ddply()  from the plyr package is used to apply  colMeans()  and ease the development


##Variables

mean() : mean values of multiple measurements of the original variables. Type: Real number

std(): Standard deviation of multiple measurements of the original variables. Type: Real number

activity_id: Identifier, identifying the activity of each subject Type: Integer Values: 1 : 6

activity_name: Name of each subject's activity Type: Factor Values: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING

subject_id : Identifier, identifying each subject Type: Integer Values: 1 : 30
