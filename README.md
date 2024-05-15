# CoERS_Submission
Final codes 

There are three code files in this submission and 5 data files that are in excel sheet format

**Distraction_Live_version1.ipynb** file contains code that does hand and mobile detection

**Drowsiness_Live_version2.ipynb** file contains code that does facial landmark detection and head direction detection. It also collects data from live feed of driver 

**Logistic_Regression.ipynb** file contains Logistic regression and Random Forest Classifier method that classifies Drowsy and Non Drowsy states. 
We need more data that is properly labelled to be of good use for Drowsy/non-drowsy classifier training

The rest five excel sheets **Kamesh_d2_21-23.xslx**, **Kamesh_d3_12-13.xslx**, **Kamesh_d3_15-17.xslx**, **Kamesh_d5_13-15.xslx**, **Saikat_d2_0-1.xslx** are datasets with labels
Create more data and label them appropriately for better results.

The changes that are to be done in each code file is mentioned on top of code file 

In **Distraction_Live_version1.ipynb** code you just need to change the address of the annotated frames based video files that needs to be saved 

In **Drowsiness_Live_version2.ipynb** code the following needs to be taken care of 

1) In Function Head_pose_Estimation it is the thresholds to look up, down, left and right

2) In Function Face_detector the times is important for threshhold of yawning and microsleep - the values I set are based on literature for microsleep and yawning is convenience

3) For eye_limit and close_limit the constants are to be changed based on experiments

4) Finally only change the excel sheet name and annotated video and live feed video storage area address for proper differentiated storage


In **Logistic_Regression.ipynb** you need to change and experiment with features to know the most important features


