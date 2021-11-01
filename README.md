# Credit_Risk_Analysis

## Overview

The purpose of this project is to use machine learning models to predict credit risk.  The machine learning models used are the RandomOverSampler, SMOTE, ClusterCentroids, and SMOTEENN.  Also the BalancedRandomForestClassifier and EasyEnsembleClassifier will be compared on how they reduce bias.

## Results

### RandomOverSampler 

![image](https://user-images.githubusercontent.com/80642682/129277682-31c4ac2d-f357-44c3-b160-e8740ff7c301.png)

![image](https://user-images.githubusercontent.com/80642682/129277726-7479ee69-1283-486b-bdff-b361200deac7.png)

![image](https://user-images.githubusercontent.com/80642682/129277825-8a65f942-360d-4f55-b0a4-05ae40ff7d43.png)


### SMOTE 

![image](https://user-images.githubusercontent.com/80642682/129277990-b828d69e-36a7-411b-8f6d-f9ddd01d65b5.png)

![image](https://user-images.githubusercontent.com/80642682/129278037-9249ff30-604e-490d-989e-c694b31b5f15.png)

![image](https://user-images.githubusercontent.com/80642682/129278093-a08d7e02-cfe2-48b4-a8d5-62a97a8f3361.png)


### ClusterCentroids 

![image](https://user-images.githubusercontent.com/80642682/129278446-07851272-e585-4609-9c7e-091808886165.png)

![image](https://user-images.githubusercontent.com/80642682/129278505-389990d6-ae65-444b-9ebf-1ee90c0ad528.png)

![image](https://user-images.githubusercontent.com/80642682/129278564-82e09b53-8eab-4091-8b03-185d135274d7.png)


### SMOTEENN 

![image](https://user-images.githubusercontent.com/80642682/129278666-d11d7076-d8ae-4389-afdf-6a1a4eee390b.png)

![image](https://user-images.githubusercontent.com/80642682/129278698-c62d9e4c-fda0-4a5a-b3e8-76b4b1814d4c.png)

![image](https://user-images.githubusercontent.com/80642682/129278743-2a47e380-945a-4b87-b759-4a98f5c5ac0e.png)


### BalancedRandomForestClassifier 

![image](https://user-images.githubusercontent.com/80642682/129278951-e41094b8-9202-4556-abe9-74e4e994f1e7.png)

![image](https://user-images.githubusercontent.com/80642682/129278989-7b3b395c-e69c-4a66-af1a-da7a9108f7e8.png)

![image](https://user-images.githubusercontent.com/80642682/129279019-da43216c-7700-49a8-8b27-4dd6786b1f9d.png)


### EasyEnsembleClassifier 

![image](https://user-images.githubusercontent.com/80642682/129279134-8265c841-bc16-4a76-9aef-ed123154d180.png)

![image](https://user-images.githubusercontent.com/80642682/129279173-3c4582f1-3dd1-489f-9dc9-7dc867b56adb.png)

![image](https://user-images.githubusercontent.com/80642682/129279218-c985a6b6-5c18-4703-9cf1-fa63629e2f3d.png)


## Summary

The machine learning models used to perform the credit risk analysis is not strong in determining if credit risk is high. However the BalancedRandomForestClassifier and the EasyEnsembleClassifier show better sensitivity to High risk credit.  For instance, the EasyEnsembleClassifier model shows an accuracy of 93%, which means it explains a majority of all high risk credit; but with a low precision, low risk credits will be mistaken as high risk. In my opinion I would not recommend any of these models to the bank to predict credit risk.

