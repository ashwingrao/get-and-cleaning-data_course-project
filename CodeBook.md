This is the Codebook for the get-and-cleaning-data_course-project

The data was tidy'ed up version of the data from the UCI HAR Dataset

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

These signals were used to estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

Only Mean and Standard Deviation measurements were used in the Tidy Data.


Variable Name                      |       Format|Variable Label                                         | Valid Range
---------------------------------  |      -----  |-------------------------------------------------------| ------------------------
Subject                            |       Int   |30 Subjects under observation                          | [1-30]       
Activity                           |       Factor|Various Activities Performed by the Subjects           | WALKING,WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING
tBodyAcc-mean()-X                  |       num   |Mean body linear acceleration and angular velocity in X| [-1,1]
tBodyAcc-mean()-Y                  |       num   |Mean body linear acceleration and angular velocity in Y| [-1,1]
tBodyAcc-mean()-Z                  |       num   |Mean body linear acceleration and angular velocity in Z| [-1,1]
tBodyAcc-std()-X                   |       num   |STD of body linear acceleration and angular velocity in| [-1,1]
tBodyAcc-std()-Y                   |       num   |STD of body linear acceleration and angular velocity in| [-1,1]
tBodyAcc-std()-Z                   |       num   |STD of body linear acceleration and angular velocity in| [-1,1]
tGravityAcc-mean()-X               |       num   |Mean gravity linear acceleration and angular velocity i| [-1,1]
tGravityAcc-mean()-Y               |       num   |Mean gravity linear acceleration and angular velocity i| [-1,1]
tGravityAcc-mean()-Z               |       num   |Mean gravity linear acceleration and angular velocity i| [-1,1]
tGravityAcc-std()-X                |       num   |STD of gravity linear acceleration and angular velocity| [-1,1]
tGravityAcc-std()-Y                |       num   |STD of gravity linear acceleration and angular velocity| [-1,1]
tGravityAcc-std()-Z                |       num   |STD of gravity linear acceleration and angular velocity| [-1,1]
tBodyAccJerk-mean()-X              |       num   |Mean Jerk Signals in X direction                       | [-1,1]
tBodyAccJerk-mean()-Y              |       num   |Mean Jerk Signals in Y direction                       | [-1,1]
tBodyAccJerk-mean()-Z              |       num   |Mean Jerk Signals in Z direction                       | [-1,1]
tBodyAccJerk-std()-X               |       num   |STD of Jerk Signals in X direction                     | [-1,1]
tBodyAccJerk-std()-Y               |       num   |STD of Jerk Signals in Y direction                     | [-1,1]
tBodyAccJerk-std()-Z               |       num   |STD of Jerk Signals in Z direction                     | [-1,1]
tBodyGyro-mean()-X                 |       num   |Mean Gyro Signals in X direction                       | [-1,1]
tBodyGyro-mean()-Y                 |       num   |Mean Gyro Signals in Y direction                       | [-1,1]
tBodyGyro-mean()-Z                 |       num   |Mean Gyro Signals in Z direction                       | [-1,1]
tBodyGyro-std()-X                  |       num   |STD of Gyro Signals in X direction                     | [-1,1]
tBodyGyro-std()-Y                  |       num   |STD of Gyro Signals in Y direction                     | [-1,1]
tBodyGyro-std()-Z                  |       num   |STD of Gyro Signals in Z direction                     | [-1,1]
tBodyGyroJerk-mean()-X             |       num   |Mean Gyro Jerk Signals in X direction                  | [-1,1]
tBodyGyroJerk-mean()-Y             |       num   |Mean Gyro Jerk Signals in Y direction                  | [-1,1]
tBodyGyroJerk-mean()-Z             |       num   |Mean Gyro Jerk Signals in Z direction                  | [-1,1]
tBodyGyroJerk-std()-X              |       num   |STD of Gyro Jerk Signals in X direction                | [-1,1]
tBodyGyroJerk-std()-Y              |       num   |STD of Gyro Jerk Signals in Y direction                | [-1,1]
tBodyGyroJerk-std()-Z              |       num   |STD of Gyro Jerk Signals in Z direction                | [-1,1]
tBodyAccMag-mean()                 |       num   |Mean Body Acceleration Magnitude                       | [-1,1]
tBodyAccMag-std()                  |       num   |STD of Body Acceleration Magnitude                     | [-1,1]
tGravityAccMag-mean()              |       num   |Mean Gravity Acceleration Magnitude                    | [-1,1]
tGravityAccMag-std()               |       num   |STD of Gravity Acceleration Magnitude                  | [-1,1]
tBodyAccJerkMag-mean()             |       num   |Mean  Acceleration Jerk Magnitude                      | [-1,1]
tBodyAccJerkMag-std()              |       num   |STD of  Acceleration Jerk Magnitude                    | [-1,1]
tBodyGyroMag-mean()                |       num   |Mean Gyro Magnitude                                    | [-1,1]
tBodyGyroMag-std()                 |       num   |STD of Gyro Magnitude                                  | [-1,1]
tBodyGyroJerkMag-mean()            |       num   |Mean Body Gyro Magnitude in Z direction                | [-1,1]
tBodyGyroJerkMag-std()             |       num   |STD of Body Gyro Magnitude in X direction              | [-1,1]
fBodyAcc-mean()-X                  |       num   |Mean Frequency Domain of Body Acceleration in X directi| [-1,1]
fBodyAcc-mean()-Y                  |       num   |Mean Frequency Domain of Body Acceleration in Y directi| [-1,1]
fBodyAcc-mean()-Z                  |       num   |Mean Frequency Domain of Body Acceleration in Z directi| [-1,1]
fBodyAcc-std()-X                   |       num   |STD Frequency Domain of Body Acceleration in X directio| [-1,1]
fBodyAcc-std()-Y                   |       num   |STD Frequency Domain of Body Acceleration in Y directio| [-1,1]
fBodyAcc-std()-Z                   |       num   |STD Frequency Domain of Body Acceleration in Z directio| [-1,1]
fBodyAcc-meanFreq()-X              |       num   |Mean Frequency Domain of Body Acceleration in X directi| [-1,1]
fBodyAcc-meanFreq()-Y              |       num   |Mean Frequency Domain of Body Acceleration in Y directi| [-1,1]
fBodyAcc-meanFreq()-Z              |       num   |Mean Frequency Domain of Body Acceleration in Z directi| [-1,1]
fBodyAccJerk-mean()-X              |       num   |Mean Frequency Domain of Acceleration Jerk in X directi| [-1,1]
fBodyAccJerk-mean()-Y              |       num   |Mean Frequency Domain of Acceleration Jerk in Y directi| [-1,1]
fBodyAccJerk-mean()-Z              |       num   |Mean Frequency Domain of Acceleration Jerk in Z directi| [-1,1]
fBodyAccJerk-std()-X               |       num   |STD Frequency Domain of Acceleration Jerk in X directio| [-1,1]
fBodyAccJerk-std()-Y               |       num   |STD Frequency Domain of Acceleration Jerk in Y directio| [-1,1]
fBodyAccJerk-std()-Z               |       num   |STD Frequency Domain of Acceleration Jerk in Z directio| [-1,1]
fBodyAccJerk-meanFreq()-X          |       num   |Mean Frequency Domain of Body Acceleration in X directi| [-1,1]
fBodyAccJerk-meanFreq()-Y          |       num   |Mean Frequency Domain of Body Acceleration in Y directi| [-1,1]
fBodyAccJerk-meanFreq()-Z          |       num   |Mean Frequency Domain of Body Acceleration in Z directi| [-1,1]
fBodyGyro-mean()-X                 |       num   |Mean Frequency Domain of Body Gyro in X direction      | [-1,1]
fBodyGyro-mean()-Y                 |       num   |Mean Frequency Domain of Body Gyro in Y direction      | [-1,1]
fBodyGyro-mean()-Z                 |       num   |Mean Frequency Domain of Body Gyro in Z direction      | [-1,1]
fBodyGyro-std()-X                  |       num   |STD of Mean Frequency Domain of Body Gyro in X directio| [-1,1]
fBodyGyro-std()-Y                  |       num   |STD of Mean Frequency Domain of Body Gyro in Y directio| [-1,1]
fBodyGyro-std()-Z                  |       num   |STD of Mean Frequency Domain of Body Gyro in Z directio| [-1,1]
fBodyGyro-meanFreq()-X             |       num   |Mean Frequency Domain of Body Gyro Mean Freq in X direc| [-1,1]
fBodyGyro-meanFreq()-Y             |       num   |Mean Frequency Domain of Body Gyro Mean Freq in Y direc| [-1,1]
fBodyGyro-meanFreq()-Z             |       num   |Mean Frequency Domain of Body Gyro Mean Freq in Z direc| [-1,1]
fBodyAccMag-mean()                 |       num   |Mean Frequency Domain of Body Acceleration Magnitude   | [-1,1]
fBodyAccMag-std()                  |       num   |STD of Mean Frequency Domain of Body Magnitude         | [-1,1]
fBodyAccMag-meanFreq()             |       num   |Mean Frequency Domain of Body Acceleration Magnitude   | [-1,1]
fBodyBodyAccJerkMag-mean()         |       num   |Mean Frequency Body Acceleration Jerk Magnitude        | [-1,1]
fBodyBodyAccJerkMag-std()          |       num   |STD of Mean Frequency of Body Acceleraion Jerk Magnitud| [-1,1]
fBodyBodyAccJerkMag-meanFreq()     |       num   |Mean Frequency of Body Acceleration Jerk Magnitude     | [-1,1]
fBodyBodyGyroMag-mean()            |       num   |Mean Frequency of Body Gyro Magnitude                  | [-1,1]
fBodyBodyGyroMag-std()             |       num   |STD of Mean Frequency of Gyro Magnitude                | [-1,1]
fBodyBodyGyroMag-meanFreq()        |       num   |Mean Frequency of Gyro Magnitude                       | [-1,1]
fBodyBodyGyroJerkMag-mean()        |       num   |Mean Frequency of Gyro Jerk Magnitude                  | [-1,1]
fBodyBodyGyroJerkMag-std()         |       num   |STD of Mean Fequency of Gyro Jerk Mag                  | [-1,1]
fBodyBodyGyroJerkMag-meanFreq()    |       num   |Mean Frequency of Body Gyro Jerk Magnitude             | [-1,1]
