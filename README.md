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



![Screen Shot 2020-10-19 at 11 42 00 PM](https://user-images.githubusercontent.com/67085043/96655344-3d5cec00-130b-11eb-83ce-bf5ee4f1d043.png)
![Screen Shot 2020-10-19 at 11 42 48 PM](https://user-images.githubusercontent.com/67085043/96655349-40f07300-130b-11eb-8c92-6490bca04adc.png)
![Screen Shot 2020-10-19 at 11 43 11 PM](https://user-images.githubusercontent.com/67085043/96655356-4483fa00-130b-11eb-81a8-2ade5511e19f.png)
![Screen Shot 2020-10-19 at 11 43 31 PM](https://user-images.githubusercontent.com/67085043/96655362-48178100-130b-11eb-9e52-3d29f4eb12e2.png)
![Screen Shot 2020-10-20 at 7 42 25 PM](https://user-images.githubusercontent.com/67085043/96655426-71381180-130b-11eb-8aa9-f58d871b3c16.png)
![Screen Shot 2020-10-20 at 7 42 07 PM](https://user-images.githubusercontent.com/67085043/96655434-75fcc580-130b-11eb-8022-19d99685a3cb.png)

Summary:

Looking at all the different models, we observe that Easy Ensemble AdaBoost Classifier performs the best and therefore we should move forward with that model for further analysis. We also notice that the recall score has the highest coefficients for predicting the loan status, meaning this would be our best model considering the high financial cost associated with False Negative in this case.

