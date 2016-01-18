This assignment reformats the Human Activity Recognition Using Smartphones Data Set into a tidy data set.

The source data is available at 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones#

The dataset is also included in the UCI HAR Dataset directory in this repo.

The tidy data in tidy_data_set.txt can be read into R with the following code:
read.table("tidy_data_set.txt", header=TRUE, colClasses=c('factor', 'factor', rep('numeric', 66)))

tidy_data_set.txt includes the combined test and training data sets.

README.md includes a walk through of the data cleansing and transformation steps used to create tidy_data_set.txt.
The tidy data set is a subset of the combined data. 
It includes only measurements on the mean and standard deviation for each measure.
It reduces the data to 68 columns (68 feature variable measurements, plus the TestSubject and Activity columns).
The size of the tidy data set was further reduced by averaging each variable for each activity and each subject.
This resulted in 180 rows of data, with a unique combination of TestSubject and Activity values in each row.

# Data dictionary
The variables in this tidy data set are a subset of the variables described in the features_info.txt file in the original data set. features_info.txt provides a more in-depth overview of the original values and how they were calculated.

TestSubject - A factor that identifies the volunteer participant.
Values: integer from 1 to 30
Activity - A factor that identifies the activity being performed
Values: Walking, WalkingUpStairs, WalkingDownStairs, Sitting, Standing, Lying
The feature variables below (#3 - #68) are each an average of the values collected for the test subject and activity specified in the data row. For each, the value is a numeric normalized and bounded within [-1, 1]
MeanBodyAccelerationXAxis - The mean of the body acceleration on the X axis.
MeanBodyAccelerationYAxis - The mean of the body acceleration on the Y axis.
MeanBodyAccelerationZAxis - The mean of the body acceleration on the Z axis.
MeanGravityAccelerationXAxis - The mean of the gravity acceleration on the X axis.
MeanGravityAccelerationYAxis - The mean of the gravity acceleration on the Y axis.
MeanGravityAccelerationZAxis - The mean of the gravity acceleration on the Z axis.
MeanBodyAccelerationJerkXAxis - The mean of the body acceleration on the X axis, derived in time to obtain Jerk signals.
MeanBodyAccelerationJerkYAxis - The mean of the body acceleration on the Y axis, derived in time to obtain Jerk signals.
MeanBodyAccelerationJerkZAxis - The mean of the body acceleration on the Z axis, derived in time to obtain Jerk signals.
MeanBodyAngularVelocityXAxis - The mean of the body angular velocity on the X axis.
MeanBodyAngularVelocityYAxis - The mean of the body angular velocity on the Y axis.
MeanBodyAngularVelocityZAxis - The mean of the body angular velocity on the Z axis.
MeanBodyAngularVelocityJerkXAxis - The mean of the body angular velocity on the X axis, derived in time to obtain Jerk signals.
MeanBodyAngularVelocityJerkYAxis - The mean of the body angular velocity on the Y axis, derived in time to obtain Jerk signals.
MeanBodyAngularVelocityJerkZAxis - The mean of the body angular velocity on the Z axis, derived in time to obtain Jerk signals.
MeanBodyAccelerationMagnitude - The mean of the body acceleration magnitude, calculated using the Euclidean norm.
MeanGravityAccelerationMagnitude - The mean of the gravity acceleration magnitude.
MeanBodyAccelerationJerkMagnitude - The mean of the body acceleration magnitude derived in time to obtain Jerk signals.
MeanBodyAngularVelocityMagnitude - The mean of the angular velocity magnitude.
MeanBodyAngularVelocityJerkMagnitude - The mean of the angular velocity magnitude derived in time to obtain Jerk signals.
MeanFFTBodyAccelerationXAxis - The mean of the body acceleration on the X axis, with a Fast Fourier Transform (FFT) applied.
MeanFFTBodyAccelerationYAxis - The mean of the body acceleration on the Y axis, with a Fast Fourier Transform (FFT) applied.
MeanFFTBodyAccelerationZAxis - The mean of the body acceleration on the Z axis, with a Fast Fourier Transform (FFT) applied.
MeanFFTBodyAccelerationJerkXAxis - The mean of the body acceleration on the X axis, derived in time to obtain Jerk signals, with a Fast Fourier Transform (FFT) applied.
MeanFFTBodyAccelerationJerkYAxis - The mean of the body acceleration on the Y axis, derived in time to obtain Jerk signals, with a Fast Fourier Transform (FFT) applied.
MeanFFTBodyAccelerationJerkZAxis - The mean of the body acceleration on the Z axis, derived in time to obtain Jerk signals, with a Fast Fourier Transform (FFT) applied.
MeanFFTBodyAngularVelocityXAxis - The mean of the body angular velocity on the X axis, with a Fast Fourier Transform (FFT) applied.
MeanFFTBodyAngularVelocityYAxis - The mean of the body angular velocity on the Y axis, with a Fast Fourier Transform (FFT) applied.
MeanFFTBodyAngularVelocityZAxis - The mean of the body angular velocity on the Z axis, with a Fast Fourier Transform (FFT) applied.
MeanFFTBodyAccelerationMagnitude - The mean of the body acceleration magnitude, with a Fast Fourier Transform (FFT) applied.
MeanFFTBodyAccelerationJerkMagnitude - The mean of the body acceleration magnitude derived in time to obtain Jerk signals, with a Fast Fourier Transform (FFT) applied.
MeanFFTBodyAngularVelocityMagnitude - The mean of the angular velocity magnitude, with a Fast Fourier Transform (FFT) applied.
MeanFFTBodyAngularVelocityJerkMagnitude - The mean of the angular velocity magnitude derived in time to obtain Jerk signals, with a Fast Fourier Transform (FFT) applied.
StandardDeviationBodyAccelerationXAxis - The standard deviation of the body acceleration on the X axis.
StandardDeviationBodyAccelerationYAxis - The standard deviation of the body acceleration on the Y axis.
StandardDeviationBodyAccelerationZAxis - The standard deviation of the body acceleration on the Z axis.
StandardDeviationGravityAccelerationXAxis - The standard deviation of the gravity acceleration on the X axis.
StandardDeviationGravityAccelerationYAxis - The standard deviation of the gravity acceleration on the Y axis.
StandardDeviationGravityAccelerationZAxis - The standard deviation of the gravity acceleration on the Z axis.
StandardDeviationBodyAccelerationJerkXAxis - The standard deviation of the body acceleration on the X axis, derived in time to obtain Jerk signals.
StandardDeviationBodyAccelerationJerkYAxis - The standard deviation of the body acceleration on the Y axis, derived in time to obtain Jerk signals.
StandardDeviationBodyAccelerationJerkZAxis - The standard deviation of the body acceleration on the Z axis, derived in time to obtain Jerk signals.
StandardDeviationBodyAngularVelocityXAxis - The standard deviation of the body angular velocity on the X axis.
StandardDeviationBodyAngularVelocityYAxis - The standard deviation of the body angular velocity on the Y axis.
StandardDeviationBodyAngularVelocityZAxis - The standard deviation of the body angular velocity on the Z axis.
StandardDeviationBodyAngularVelocityJerkXAxis - The standard deviation of the body angular velocity on the X axis, derived in time to obtain Jerk signals.
StandardDeviationBodyAngularVelocityJerkYAxis - The standard deviation of the body angular velocity on the Y axis, derived in time to obtain Jerk signals.
StandardDeviationBodyAngularVelocityJerkZAxis - The standard deviation of the body angular velocity on the Z axis, derived in time to obtain Jerk signals.
StandardDeviationBodyAccelerationMagnitude - The standard deviation of the body acceleration magnitude, calculated using the Euclidean norm.
StandardDeviationGravityAccelerationMagnitude - The standard deviation of the gravity acceleration magnitude.
StandardDeviationBodyAccelerationJerkMagnitude - The standard deviation of the body acceleration magnitude derived in time to obtain Jerk signals.
StandardDeviationBodyAngularVelocityMagnitude - The standard deviation of the angular velocity magnitude.
StandardDeviationBodyAngularVelocityJerkMagnitude - The standard deviation of the angular velocity magnitude derived in time to obtain Jerk signals.
StandardDeviationFFTBodyAccelerationXAxis - The standard deviation of the body acceleration on the X axis, with a Fast Fourier Transform (FFT) applied.
StandardDeviationFFTBodyAccelerationYAxis - The standard deviation of the body acceleration on the Y axis, with a Fast Fourier Transform (FFT) applied.
StandardDeviationFFTBodyAccelerationZAxis - The standard deviation of the body acceleration on the Z axis, with a Fast Fourier Transform (FFT) applied.
StandardDeviationFFTBodyAngularVelocityJerkXAxis - The standard deviation of the body angular velocity on the X axis, derived in time to obtain Jerk signals, with a Fast Fourier Transform (FFT) applied.
StandardDeviationFFTBodyAngularVelocityJerkYAxis - The standard deviation of the body angular velocity on the Y axis, derived in time to obtain Jerk signals, with a Fast Fourier Transform (FFT) applied.
StandardDeviationFFTBodyAngularVelocityJerkZAxis - The standard deviation of the body angular velocity on the Z axis, derived in time to obtain Jerk signals, with a Fast Fourier Transform (FFT) applied.
StandardDeviationFFTBodyAngularVelocityXAxis - The standard deviation of the body angular velocity on the X axis, with a Fast Fourier Transform (FFT) applied.
StandardDeviationFFTBodyAngularVelocityYAxis - The standard deviation of the body angular velocity on the Y axis, with a Fast Fourier Transform (FFT) applied.
StandardDeviationFFTBodyAngularVelocityZAxis - The standard deviation of the body angular velocity on the Z axis, with a Fast Fourier Transform (FFT) applied.
StandardDeviationFFTBodyAccelerationMagnitude - The standard deviation of the body acceleration magnitude, with a Fast Fourier Transform (FFT) applied.
StandardDeviationFFTBodyAccelerationJerkMagnitude - The standard deviation of the body acceleration magnitude derived in time to obtain Jerk signals, with a Fast Fourier Transform (FFT) applied.
StandardDeviationFFTBodyAngularVelocityMagnitude - The standard deviation of the angular velocity magnitude, with a Fast Fourier Transform (FFT) applied.
StandardDeviationFFTBodyAngularVelocityJerkMagnitude - The standard deviation of the angular velocity magnitude derived in time to obtain Jerk signals, with a Fast Fourier Transform (FFT) applied.

Details on variable naming
Feature variable names in the tidy data (vs. the names in the source data described in features_info.txt) are designed to make it easier for consumers of the data to understand the measurement of each column. The names use the following conventions:
The first word(s) indicates the type of metric, Mean or StandardDeviation
Next, FFT is included, if applicable, to indicate that the measurement had a Fast Fourier Transform (FFT) applied.
Either Body or Gravity is included to indicate the type of signal
Either Acceleration or AngularVelocity is included to indicate the type of measurement.
The word "Gyro" is replaced with "AngularVelocity" to specify what the gyroscope measures.
Jerk indicates a measure where body linear acceleration and angular velocity were derived in time to obtain Jerk signals
Magnitude indicates a magnitude calculation
XAxis, YAxis, and ZAxis indicate a measurement for the X, Y, or Z axis.

