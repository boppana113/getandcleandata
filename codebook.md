## CodeBook : Tidy dataset description - Features

### Tidydata

The tidydata set is a text csv file (generated through write.table() function)

* Filename: tidydata.txt
    * File contains header
    * ';' separated file
    * '"' quote charater
* Columns : 68 variables - subject, activity, and all 66 mean or standard deviation for each measurement
* Rows : 180 observations (plus header line)

### Features

* 'subject'
    * Subject (individual) participating to study.
    * Field does not contain real name but an Id to preserve anonymous
        * Its range is from 1 to 30
    * Type : integer
    * Unit : NA, identifier
* 'activity'
    * Measured activity
    * Type : Factor
    * Factor levels:
        * "WALKING"
        * "WALKING_UPSTAIRS"
        * "WALKING_DOWNSTAIRS"
        * "SITTING"
        * "STANDING"
        * "LAYING"
    * Unit : String factor
* 'tBodyAccMeanX'
    * Body Acceleration mean - X axis
    * Unit : 'g' gravity, acceleration
* 'tBodyAccMeanY'
    * Body Acceleration mean - Y axis
    * Unit : 'g' gravity, acceleration
* 'tBodyAccMeanZ'
    * Body Acceleration mean - Z axis
    * Unit : 'g' gravity, acceleration
* 'tBodyAccStdX'
    * Body acceleration standard deviation - X axis
    * Unit : 'g' gravity, acceleration
* 'tBodyAccStdY'
    * Body acceleration standard deviation - Y axis
    * Unit : 'g' gravity, acceleration
* 'tBodyAccStdZ'
    * Body acceleration standard deviation - Z axis
    * Unit : 'g' gravity, acceleration
* 'tGravityAccMeanX'
    * Gravity acceleration mean - X axis
    * Unit : 'g' gravity, acceleration
* 'tGravityAccMeanY'
    * Gravity acceleration mean - Y axis
    * Unit : 'g' gravity, acceleration
* 'tGravityAccMeanZ'
    * Gravity acceleration mean - Z axis
    * Unit : 'g' gravity, acceleration
* 'tGravityAccStdX'
    * Gravity acceleration standard deviation - X axis
    * Unit : 'g' gravity, acceleration
* 'tGravityAccStdY'
    * Gravity acceleration standard deviation - Y axis
    * Unit : 'g' gravity, acceleration
* 'tGravityAccStdZ'
    * Gravity acceleration standard deviation - Z axis
    * Unit : 'g' gravity, acceleration
* 'tBodyAccJerkMeanX'
    * Body acceleration jerk mean - X axis
    * Unit : 'g' gravity, acceleration
* 'tBodyAccJerkMeanY'
    * Body acceleration jerk mean - Y axis
    * Unit : 'g' gravity, acceleration
* 'tBodyAccJerkMeanZ'
    * Body acceleration jerk mean - Z axis
    * Unit : 'g' gravity, acceleration
* 'tBodyAccJerkStdX'
    * Body acceleration jerk standard deviation - X axis
    * Unit : 'g' gravity, acceleration
* 'tBodyAccJerkStdY'
    * Body acceleration jerk standard deviation - Y axis
    * Unit : 'g' gravity, acceleration
* 'tBodyAccJerkStdZ'
    * Body acceleration jerk standard deviation - Z axis
    * Unit : 'g' gravity, acceleration
* 'tBodyGyroMeanX'
    * Body gyro (angular velocity vector) mean - X axis
    * Unit : radians/second
* 'tBodyGyroMeanY'
    * Body gyro (angular velocity vector) mean - Y axis
    * Unit : radians/second
* 'tBodyGyroMeanZ'
    * Body gyro (angular velocity vector) mean - Z axis
    * Unit : radians/second
* 'tBodyGyroStdX'
    * Body gyro (angular velocity vector) standard deviation - X axis
    * Unit : radians/second
* 'tBodyGyroStdY'
    * Body gyro (angular velocity vector) standard deviation - Y axis
    * Unit : radians/second
* 'tBodyGyroStdZ'
    * Body gyro (angular velocity vector) standard deviation - Z axis
    * Unit : radians/second
* 'tBodyGyroJerkMeanX'
    * Body gyro (angular velocity vector) jerk mean - X axis
    * Unit : radians/second
* 'tBodyGyroJerkMeanY'
    * Body gyro (angular velocity vector) jerk mean - Y axis
    * Unit : radians/second
* 'tBodyGyroJerkMeanZ'
    * Body gyro (angular velocity vector) jerk mean - Z axis
    * Unit : radians/second
* 'tBodyGyroJerkStdX'
    * Body gyro (angular velocity vector) jerk standard deviation - X axis
    * Unit : radians/second
* 'tBodyGyroJerkStdY'
    * Body gyro (angular velocity vector) jerk standard deviation - Y axis
    * Unit : radians/second
* 'tBodyGyroJerkStdZ'
    * Body gyro (angular velocity vector) jerk standard deviation - Z axis
    * Unit : radians/second
* 'tBodyAccMagMean'
    * Body acceleration magnitude mean
    * Unit : 'g' gravity, acceleration
* 'tBodyAccMagStd'
    * Body acceleration magnitude standard deviation
    * Unit : 'g' gravity, acceleration
* 'tGravityAccMagMean'
    * Gravity acceleration magnitude mean
    * Unit : 'g' gravity, acceleration
* 'tGravityAccMagStd'
    * Gravity acceleration magnitude standard deviation
    * Unit : 'g' gravity, acceleration
* 'tBodyAccJerkMagMean'
    * Body acceleration magnitude jerk mean
    * Unit : 'g' gravity, acceleration
* 'tBodyAccJerkMagStd'
    * Body acceleration magnitude jerk standard deviation
    * Unit : 'g' gravity, acceleration
* 'tBodyGyroMagMean'
    * Body gyro (angular velocity vector) magnitude mean
    * Unit : radians/second
* 'tBodyGyroMagStd'
    * Body gyro (angular velocity vector) magnitude standard deviation
    * Unit : radians/second
* 'tBodyGyroJerkMagMean'
    * Body gyro (angular velocity vector) jerk magnitude mean
    * Unit : radians/second
* 'tBodyGyroJerkMagStd'
    * Body gyro (angular velocity vector) jerk magnitude standard deviation
    * Unit : radians/second
* 'fBodyAccMeanX'
    * Body acceleration mean - X axis
    * Unit : 'g' gravity, acceleration
* 'fBodyAccMeanY'
    * Body acceleration mean - Y axis
    * Unit : 'g' gravity, acceleration
* 'fBodyAccMeanZ'
    * Body acceleration mean - Z axis
    * Unit : 'g' gravity, acceleration
* 'fBodyAccStdX'
    * Body acceleration standard deviation - X axis
    * Unit : 'g' gravity, acceleration
* 'fBodyAccStdY'
    * Body acceleration standard deviation - Y axis
    * Unit : 'g' gravity, acceleration
* 'fBodyAccStdZ'
    * Body acceleration standard deviation - Z axis
    * Unit : 'g' gravity, acceleration
* 'fBodyAccJerkMeanX'
    * Body acceleration jerk mean - X axis
    * Unit : 'g' gravity, acceleration
* 'fBodyAccJerkMeanY'
    * Body acceleration jerk mean - Y axis
    * Unit : 'g' gravity, acceleration
* 'fBodyAccJerkMeanZ'
    * Body acceleration jerk mean - Z axis
    * Unit : 'g' gravity, acceleration
* 'fBodyAccJerkStdX'
    * Body acceleration jerk standard deviation - X axis
    * Unit : 'g' gravity, acceleration
* 'fBodyAccJerkStdY'
    * Body acceleration jerk standard deviation - Y axis
    * Unit : 'g' gravity, acceleration
* 'fBodyAccJerkStdZ'
    * Body acceleration jerk standard deviation - Z axis
    * Unit : 'g' gravity, acceleration
* 'fBodyGyroMeanX'
    * Body gyro (angular velocity vector) mean - X axis
    * Unit : radians/second
* 'fBodyGyroMeanY'
    * Body gyro (angular velocity vector) mean - Y axis
    * Unit : radians/second
* 'fBodyGyroMeanZ'
    * Body gyro (angular velocity vector) mean - Z axis
    * Unit : radians/second
* 'fBodyGyroStdX'
    * Body gyro (angular velocity vector) standard deviation - X axis
    * Unit : radians/second
* 'fBodyGyroStdY'
    * Body gyro (angular velocity vector) standard deviation - Y axis
    * Unit : radians/second
* 'fBodyGyroStdZ'
    * Body gyro (angular velocity vector) standard deviation - Z axis
    * Unit : radians/second
* 'fBodyBodyAccMagMean'
    * Body body accelation magnitude mean
    * Unit : 'g' gravity, acceleration
* 'fBodyBodyAccMagStd'
    * Body body accelation magnitude standard deviation
    * Unit : 'g' gravity, acceleration
* 'fBodyBodyAccJerkMagMean'
    * Body body accelation jerk magnitude mean
    * Unit : 'g' gravity, acceleration
* 'fBodyBodyAccJerkMagStd'
    * Body body accelation jerk magnitude standard deviation
    * Unit : 'g' gravity, acceleration
* 'fBodyBodyGyroMagMean'
    * Body body gyro (angular velocity vector) magnitude mean
    * Unit : radians/second
* 'fBodyBodyGyroMagStd'
    * Body body gyro (angular velocity vector) magnitude standard deviation
    * Unit : radians/second
* 'fBodyBodyGyroJerkMagMean'
    * Body body gyro (angular velocity vector) jerk magnitude mean
    * Unit : radians/second
* 'fBodyBodyGyroJerkMagStd'
    * Body body gyro (angular velocity vector) jerk magnitude standard deviation
    * Unit : radians/second