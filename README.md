# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:

Apply machine learning to solve a real-world credit card risk analysis. We will use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. With the he credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Next, we used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm and compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 


## Results:
Credit card credit dataset (LoanStats_2019Q1.csv) hold 115,675 loan applications. All null values columnd and row were drpped.This reduced the dataset to 68,817 total . We used the "loan status" to determine whether the application was considered "low" or "high" risk. 

![Screenshot 2022-12-07 at 11 41 04 PM](https://user-images.githubusercontent.com/110786136/206366850-7f09124f-34cd-45b3-b24a-7eb7c8f79e9a.png)

Balance accuracy score and the precision and recall scores of all six machine learning models; 

RandomOverSampler: 
![Screenshot 2022-12-07 at 11 52 00 PM](https://user-images.githubusercontent.com/110786136/206368138-521b849c-f873-4445-9c14-581fd3e9e2bf.png)
SMOTE: 
![Screenshot 2022-12-07 at 11 54 34 PM](https://user-images.githubusercontent.com/110786136/206368511-a2d9ce6c-431a-4a4f-b477-8d76f067f20c.png)

ClusterCentroids: 
![Screenshot 2022-12-08 at 12 04 52 AM](https://user-images.githubusercontent.com/110786136/206369934-4836c29f-1fbb-44f8-a716-7a39c6e47741.png)

SMOTEENN: 
![Screenshot 2022-12-07 at 11 56 50 PM](https://user-images.githubusercontent.com/110786136/206368831-316c5330-5f38-45b8-8e12-966ee558edef.png)

BalancedRandomForestClassifer:
![Screenshot 2022-12-07 at 11 59 18 PM](https://user-images.githubusercontent.com/110786136/206369183-4f0aafe4-c2be-4a3a-b61a-f72d17543132.png)

EasyEnsembleClassifer: ![Screenshot 2022-12-07 at 11 58 06 PM](https://user-images.githubusercontent.com/110786136/206369021-f77cf424-eacf-4bc1-a60a-55fd93bfb13f.png)

## Summary:
 EasyEsembleClassifer method is the best accuracy score with a .93% meaning that the model was correct 77.6% of the time.
