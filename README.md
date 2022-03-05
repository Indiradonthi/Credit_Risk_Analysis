# Credit_Risk_Analysis

## Overview

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once done, evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

- Deliverable 1: Use Resampling Models to Predict Credit Risk
- Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
- Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
- Deliverable 4: A Written Report on the Credit Risk Analysis

## Results

### Models to Predict Credit Risk

- ### Oversampling Algorithms

![image](https://user-images.githubusercontent.com/90879122/156866290-b3a7a36a-d512-4926-ac72-8bf179bcd453.png)


![image](https://user-images.githubusercontent.com/90879122/156865692-0fb22c7c-bef2-4796-a78b-21d0e217f15f.png)

- ### SMOTE Oversampling

![image](https://user-images.githubusercontent.com/90879122/156866334-4d32b75b-bb7e-4ad5-898f-f61fa656a76d.png)


![image](https://user-images.githubusercontent.com/90879122/156865761-c955e218-7a59-4b34-96b0-54296144c4e4.png)

Balanced Accuracy Score 64%

- ### Undersampling

![image](https://user-images.githubusercontent.com/90879122/156866368-15352f03-5812-46a1-9752-9d0fc61f8f93.png)


![image](https://user-images.githubusercontent.com/90879122/156865803-668c15a8-b406-4658-a1fa-7e2e9c75b5d5.png)

Balanced Accuracy Score 52%

- ### Combination (Over and Under Sampling)


![image](https://user-images.githubusercontent.com/90879122/156866428-a0b5a1c5-d560-4880-aa54-9dbb14f2bbb2.png)


![image](https://user-images.githubusercontent.com/90879122/156865887-6465eaf7-bc14-4e9a-856e-8c0acc9046d1.png)


Balanced Accuracy Score 62%

- ### Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/90879122/156866570-bff6978f-8267-482b-9f97-eff87c243bd1.png)


![image](https://user-images.githubusercontent.com/90879122/156865929-3e5443d9-bf30-4b80-8caf-0a5a4d3c2c50.png)

Balanced Accuracy Score 89%

- ### Easy Ensemble AdaBoost Classifier

![image](https://user-images.githubusercontent.com/90879122/156866027-b01344c7-825f-43fe-a510-64ab8eaec6ae.png)


![image](https://user-images.githubusercontent.com/90879122/156865955-2a1f1924-32e8-4f97-a992-e5960163c8df.png)


## Summary


In summary, the Easy Ensemble AdaBoost Classifier model may be the best one for preventing fraudulent loan applications because the model's accuracy is high at 92%, and the precision and recall are good enough to state that the model will be good at classifying fraudulent loan applications. It should be noted that despite not being very accurate the oversampling algoritms were also extra time consuming.












