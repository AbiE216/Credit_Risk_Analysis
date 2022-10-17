# Credit_Risk_Analysis
## Overview
This assignment was to gain familiarity with unsupervised learning, and how to process the results that it creates. Including Confusion Matrices, balanced accuracy scores, and classification reports. 

## Results
The data set provided has very few data points on high risk credit, while it has many many samples on low risk credit. Thus various types of unsupervised Machine Learning was used to try and find patterns based on this data. 
### Definitions:
 - Balanced Accuracy Score: used to determine the number of True positive rate, between the predicted and the actual data set. 
 - Precision Score: Precision is the number of data points that are relevant from what the model collected.
 - Recall Score: Recall is the number of data points that the model identified as correct from the total relevant data points. 
### Naive Oversampling
![Naive Random Oversampling](https://user-images.githubusercontent.com/106715300/196280535-c4674171-4c40-4f8c-9c4f-3c9ebbce0c02.png)
Naive oversampling: creates data points to try to balance the data set proportions. 
  - Balanced Accuracy Score: .657
  - Precision: high-risk: .01   low-risk: 1.0
  - Recall: high-risk: .71    low-risk: .60
### SMOTE Oversampling
![Smote Oversampling](https://user-images.githubusercontent.com/106715300/196284958-0ae00b87-38cb-4107-b4bd-6f180cfe0445.png)
SMOTE Oversampling: synthesizes new data points to try and balance the data set proportions.
  - Balanced Accuracy Score: .662
  - Precision: high-risk: .01   low-risk: 1.0
  - Recall: high-risk: .63    low-risk: .69
 ### Undersampling 
 ![Undersampling](https://user-images.githubusercontent.com/106715300/196285449-a5812979-c154-47cb-9aa8-07b9fd88a72a.png)
 Undersampling: Cluster Centroids, takes pockets of data from the larger sample and condenses them down, to create a smaller sample to compare evenly.
   - Balanced Accuracy Score: .544
   - Precision: high-risk: .01   low-risk: 1.0
   - Recall: high-risk: .69    low-risk: .40
