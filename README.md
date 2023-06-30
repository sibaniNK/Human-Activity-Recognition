# Human-Activity-Recognition

Human activity recognition using smartphone data involves using machine learning techniques to classify different physical activities based on data collected from the sensors in a smartphone. The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKINGUPSTAIRS, WALKINGDOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers were selected for generating the training data and 30% the test data. 

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

The goal of the project is to use this data to train a machine learning model that can accurately classify the activities performed by the study participants. To do this, we will need to pre-process the data to extract features that are relevant for distinguishing between the different activities. We can then use these features to train a machine learning model, such as a decision tree, random forest, support vector machine, or neural network. Finally, we can evaluate the performance of our model on a separate test dataset to see how well it generalizes to new examples of activities. 

# Data pre-processing:

In Data pre-processing we’ll perform various activities like:

Checking Duplicates

Checking and removing NULL/missing values

Checking for class imbalanc

# EDA

EDA might involve visualizing the data to see how the different features vary across different activities, or computing summary statistics such as mean and standard deviation to understand the distribution of the data. We can start by visualizing the data for each feature separately, such as by creating histograms or box plots. This can help us understand the distribution of the data and identify any outliers or anomalies. We could also create scatter plots to see how the different features are correlated with each other, or create time series plots to see how the data varies over time.

# Objectives:
 
Human activity recognition (HAR) aims to classify a person's actions from a series of measurements captured by sensors. Nowadays, collecting this type of data is not an arduous task. With the growth of the Internet of Things, almost everyone has some gadget that monitors their movements. It can be a Smartwatch, a Pulsometer, or even a smartphone. The machine learning model used for activity recognition relies on top of the devices' available sensors. However, analyzing this data can be a big challenge. Indeed, human activities are complex.
These are some of the data you could use:

•	Body acceleration.

•	Gravity acceleration.

•	Body angular speed.

•	Body angular acceleration.

# Benefits:

 MONITOR HEALTH :

Analyze the activity of a person from the information collected by different devices.

 DISCOVER ACTIVITY PATTERNS:
 
Discover which are the variables that determine which activity a person is doing.

 IMPROVE WELLBEING:
Design individualized exercise tables to improve the health of a person.

# Conclusions
Human activity recognition has a wide range of uses because of its impact on wellbeing.
It is becoming a fundamental tool in healthcare solutions such as preventing obesity or caring for elderly persons.





















