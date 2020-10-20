# Credit_Risk_Analysis


Overview:
The purpose of this assignment was to test different techniques to solve credit card risk.


Results:


Naive Random Oversampling:
The precision score are 1.00 for predicting low-risk and 0.01 for predicting high-risk. The recall score is about 0.54 for low-risk and 0.60 for high risk. The balanced accuracy score is 0.57, which is pretty low.

SMOTE Oversampling:
The precision score are 1.00 for predicting low-risk and 0.01 for predicting high-risk. The recall score is about 0.65 for low-risk and 0.57 for high risk. The balanced accuracy score is 0.614, which is pretty low.

Undersampling:
The precision score are 0.99 for predicting low-risk and 0.01 for predicting high-risk. The recall score is about the same (0.46 for low-risk and 0.54 for high-risk) for both categories. The balanced accuracy score is 0.61, which is low.

Combination Sampling:
The precision score are 1.00 for predicting low-risk and 0.01 for predicting high-risk. The recall score is about the same (0.61 for low-risk and 0.64 for high-risk) for both categories. The balanced accuracy score is 0.499, which is pretty low.

Balanced Random Forest Classifier:
The precision score are 0.99 for predicting low-risk and 0.00 for predicting high-risk. The recall score is 1.00 for low-risk and 0.00 for high-risk. The balanced accuracy score is 0.499, which is very high.

Easy Ensemble AdaBoost Classifier:
The precision score are 1.00 for predicting low-risk and 1.00 for predicting high-risk. The recall score is 1.00 for low-risk and 1.00 for high-risk. The balanced accuracy score is 1.0, which is very high.



Summary:

Looking at all the different models, we observe that Easy Ensemble AdaBoost Classifier performs the best and therefore we should move forward with that model for further analysis. We also notice that the recall score has the highest coefficients for predicting the loan status, meaning this would be our best model considering the high financial cost associated with False Negative in this case.
