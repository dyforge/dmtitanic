Kaggle Titanic Challenge
Problem Statement: Use the Titanic passenger data (name, age, price of ticket, etc) to try to predict who will survive and who will die.


Data: The data is divided into three files as listed below:

Train.csv : Contains information of passengers (like passenger id, age, fare, name) on boarded titanic. It also contains information whether the passenger survived or not.

Test.csv : Apply model on test dataset to predict whether they survived or not

gender_submission.csv : Sample file for submission


Data Preprocessing and Heat Map for data correlation:


  Data Preprocessing step: checking for NA and Null value in training data set. Generated correlation heat map to find the features having positive     correlation value.


  Creating new data frame from existing and removing the NA, NULL values in Test Dataset with mean value for the column. Fare attribute has positive correlation value.




Pattern Analysis:


Based on gender_submission.csv, Majority of female passengers survived and only a small fraction of male passengers survived  as depicted in below.




 Models Used:


The models listed below were used for prediction of survival of passengers in Titanic. Different features and hyper-parameters were used to increase the accuracy of the predictions. 

Random Forest model

K-Neighbors

SVM

Model and  their Accuracy : 


![Screen Shot 2022-10-11 at 4 30 26 PM](https://user-images.githubusercontent.com/90368096/195202266-04d6739d-697a-4e44-ba5b-0792db316aba.png)



Kaggle Submission:
![Screen Shot 2022-10-07 at 7 58 43 PM](https://user-images.githubusercontent.com/90368096/195202451-202fb1f1-7c42-4cd3-ad57-e7c6c979171a.png)



References:

https://www.kaggle.com/code/alexisbcook/titanic-tutorial/notebook 

https://scikit-learn.org/stable/modules/neighbors.html 

https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html 

https://www.kaggle.com/code/ignacioch/predicting-vg-hits-1-million-sales-with-lr-rfc/notebook?scriptVersionId=0 - for heat map generation

