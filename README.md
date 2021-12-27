# Porto-Seguro-Safe-Driver-Prediction
Code used for the Kaggle competion: "Porto Seguro's Safe Driver Prediction".
This was a predictive analysis project to determine how likely a given driver is to claim insurance in the coming year.
Classification algorithms used - Xgboost, Random forest classifier, Artificial Neural Networks and Logistic regression.
The train and test data are available on the Kaggle page : https://www.kaggle.com/c/porto-seguro-safe-driver-prediction/data.
Training dataset had exterme class imbalance as the number of records with claims is always significantly lower than non-claims. 
Class balancing approaches used : Undersampling using Kmeans, Random undersampling, Synthetic Minority Oversampling Technique.
Feature reduction approaches used : Feature importance obtained from RandomForestclassifier, Logistic regression 
                                    and Frequency and binary encoding.
Best result obtained using the following combination: 
                                     Class imbalance: Random undersampling.
                                   Feature selection: Binary and frequency encoding.
                                Prediction algorithm: Xgboost.
