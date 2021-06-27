# Credit_Risk_Analysis

Overview of the loan prediction risk analysis:

The purpose of this analysis is well defined (4 pt)
Results:

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)

Higher the Accuracy score - the more incidences of correct predictions (closer to 1)



- Total Credit Risks

<img width="185" alt="total # credit accounts" src="https://user-images.githubusercontent.com/78769464/123560142-2f971a80-d766-11eb-8478-483f679ef74c.png">

- Random OverSampling vs UnderSampling
### Over
<img width="653" alt="random oversampling" src="https://user-images.githubusercontent.com/78769464/123560154-4178bd80-d766-11eb-82cf-d1e3bf4d118a.png">

**Balanced Accuracy Score = 65%
Precision = 99%
Recall Score = 59%**


### Under
<img width="653" alt="Undersampling" src="https://user-images.githubusercontent.com/78769464/123560157-450c4480-d766-11eb-88ee-c4cf39eb34cf.png">

**Balanced Accuracy Score = 65%
Precision = 99%
Recall Score = 40%**


- SMOTE Oversampling

<img width="656" alt="Smote oversampling" src="https://user-images.githubusercontent.com/78769464/123560165-56ede780-d766-11eb-8fe9-465c6719ec7d.png">

**Balanced Accuracy Score = 66%
Precision = 99%
Recall Score = 69%**

-SMOTEENN Over/Under Sampling

<img width="661" alt="Smoteenn over:under sampling" src="https://user-images.githubusercontent.com/78769464/123560175-63724000-d766-11eb-9e12-1c7537226dba.png">

**Balanced Accuracy Score = 54%
Precision = 99%
Recall Score = 57%**

- Balanced Random Forest Classifier

<img width="657" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/78769464/123560194-7258f280-d766-11eb-8d9b-b73528bab242.png">

**Balanced Accuracy Score = 79%
Precision = 99%
Recall Score = 87%**

- Easy Emsemble Classifier

<img width="655" alt="Easy emsemble Classifier" src="https://user-images.githubusercontent.com/78769464/123560202-7c7af100-d766-11eb-9fe8-b7e6b7c9f3f5.png">

**Balanced Accuracy Score = 93%
Precision = 99%
Recall Score = 94%**

## Summary
I would recommend the Easy Emsemble Classifier given is drastically higher balanced accuracy score. With over 20% higher than the comparable statistics of the other models. 
