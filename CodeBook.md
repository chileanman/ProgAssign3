# Code Book

This code book summarizes the resulting data fields in `TidyData.txt`.

## Identifiers

* `subject` - The ID of the test subject
* `activityName` - The type of activity performed when the corresponding measurements were taken

## Measurements

"subject"                                        "activityName"                                  
 "activityNum"                                    "timeBodyAccelerometer-MEAN()-X"                
 "timeBodyAccelerometer-MEAN()-Y"                 "timeBodyAccelerometer-MEAN()-Z"                
 "timeBodyAccelerometer-SD()-X"                   "timeBodyAccelerometer-SD()-Y"                  
 "timeBodyAccelerometer-SD()-Z"                   "timeGravityAccelerometer-MEAN()-X"             
 "timeGravityAccelerometer-MEAN()-Y"              "timeGravityAccelerometer-MEAN()-Z"             
 "timeGravityAccelerometer-SD()-X"                "timeGravityAccelerometer-SD()-Y"               
 "timeGravityAccelerometer-SD()-Z"                "timeBodyAccelerometerJerk-MEAN()-X"            
 "timeBodyAccelerometerJerk-MEAN()-Y"             "timeBodyAccelerometerJerk-MEAN()-Z"            
 "timeBodyAccelerometerJerk-SD()-X"               "timeBodyAccelerometerJerk-SD()-Y"              
 "timeBodyAccelerometerJerk-SD()-Z"               "timeBodyGyroscope-MEAN()-X"                    
 "timeBodyGyroscope-MEAN()-Y"                     "timeBodyGyroscope-MEAN()-Z"                    
 "timeBodyGyroscope-SD()-X"                       "timeBodyGyroscope-SD()-Y"                      
 "timeBodyGyroscope-SD()-Z"                       "timeBodyGyroscopeJerk-MEAN()-X"                
 "timeBodyGyroscopeJerk-MEAN()-Y"                 "timeBodyGyroscopeJerk-MEAN()-Z"                
 "timeBodyGyroscopeJerk-SD()-X"                   "timeBodyGyroscopeJerk-SD()-Y"                  
 "timeBodyGyroscopeJerk-SD()-Z"                   "timeBodyAccelerometerMagnitude-MEAN()"         
 "timeBodyAccelerometerMagnitude-SD()"            "timeGravityAccelerometerMagnitude-MEAN()"      
 "timeGravityAccelerometerMagnitude-SD()"         "timeBodyAccelerometerJerkMagnitude-MEAN()"     
 "timeBodyAccelerometerJerkMagnitude-SD()"        "timeBodyGyroscopeMagnitude-MEAN()"             
 "timeBodyGyroscopeMagnitude-SD()"                "timeBodyGyroscopeJerkMagnitude-MEAN()"         
 "timeBodyGyroscopeJerkMagnitude-SD()"            "frequencyBodyAccelerometer-MEAN()-X"           
 "frequencyBodyAccelerometer-MEAN()-Y"            "frequencyBodyAccelerometer-MEAN()-Z"           
 "frequencyBodyAccelerometer-SD()-X"              "frequencyBodyAccelerometer-SD()-Y"             
 "frequencyBodyAccelerometer-SD()-Z"              "frequencyBodyAccelerometerJerk-MEAN()-X"       
 "frequencyBodyAccelerometerJerk-MEAN()-Y"        "frequencyBodyAccelerometerJerk-MEAN()-Z"       
 "frequencyBodyAccelerometerJerk-SD()-X"          "frequencyBodyAccelerometerJerk-SD()-Y"         
 "frequencyBodyAccelerometerJerk-SD()-Z"          "frequencyBodyGyroscope-MEAN()-X"               
 "frequencyBodyGyroscope-MEAN()-Y"                "frequencyBodyGyroscope-MEAN()-Z"               
 "frequencyBodyGyroscope-SD()-X"                  "frequencyBodyGyroscope-SD()-Y"                 
 "frequencyBodyGyroscope-SD()-Z"                  "frequencyBodyAccelerometerMagnitude-MEAN()"    
 "frequencyBodyAccelerometerMagnitude-SD()"       "frequencyBodyAccelerometerJerkMagnitude-MEAN()"
 "frequencyBodyAccelerometerJerkMagnitude-SD()"   "frequencyBodyGyroscopeMagnitude-MEAN()"        
 "frequencyBodyGyroscopeMagnitude-SD()"           "frequencyBodyGyroscopeJerkMagnitude-MEAN()"    
 "frequencyBodyGyroscopeJerkMagnitude-SD()"      

## Activity Labels

* `WALKING` (value `1`): subject was walking during the test
* `WALKING_UPSTAIRS` (value `2`): subject was walking up a staircase during the test
* `WALKING_DOWNSTAIRS` (value `3`): subject was walking down a staircase during the test
* `SITTING` (value `4`): subject was sitting during the test
* `STANDING` (value `5`): subject was standing during the test
* `LAYING` (value `6`): subject was laying down during the test
