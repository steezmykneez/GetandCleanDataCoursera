Getting and Cleaning Data (Coursera). Course Project Codebook
Original Data
There original data comes from the smartphone accelerometer and gyroscope 3-axial raw signals, which have been processed using various signal processing techniques to measurement vector consisting of 561 features. For detailed description of the original dataset, please see features_info.txt in the zipped dataset file.

source
description
Conventions followed
Processing code and dataset variable naming follows the conventions described in Google R Styde Guide.
-(mean|std)\\(

This regular expression selects 66 features from the original data set. Combined with subject identifiers subject and activity labels label, this makes up the 68 variables of the processed raw data set.

The training and test subsets of the original dataset were combined to produce final raw dataset.

Replaced -mean with Mean
Replaced -std with Std

It should be noted that the variable names are formatted in camelCase, as described in Google R Styde Guide.

Sample of renamed variables compared to original variable name
Raw data	Tidy data
subject	subject
label	label

