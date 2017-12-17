# Porto-Seguro-Safe-Driver-Prediction
Code used for the Kaggle competion: "Porto Seguro's Safe Driver Prediction". View readme for details of the approacah used.
This was a predictive analysis project to predict how likely a given driver is likely to claim insurance in the coming year.
Classification algorithms used - Xgboost, Random forest classifier, Artificial Neural Networks and Logistic regression.
The train and test data are available on the Kaggle page : https://www.kaggle.com/c/porto-seguro-safe-driver-prediction/data.
The train data had extrme class imbalance. 
Class balancing approaches used : Undersampling using Kmeans, Random undersampling, Synthetic Minority Oversampling Technique.
Feature reduction approaches used : Fearute importances obtained from RandomForestclassifier, Logistic regression 
                                    and Frequency and binary encoding.
Best result obtained using the following combination: 
                                     Class imbalance: Random undersampling.
                                   Feature selection: Binary and frequency encoding.
                                Prediction algorithm: Xgboost.
