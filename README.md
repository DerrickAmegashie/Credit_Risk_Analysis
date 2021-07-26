# Credit_Risk_Analysis

## Overview of the Analysis
The project involved analysisg the loan_stats dataset to predict whether an individual fell either in the low or high risk category. I used the imbalanced-learn and scikit-learn libraries to debelop and analyze models using the resamling method. The overall purpose was to use multiple machine learning tools to access credit card information to uncover and prevent credit risk.


## Results
- Naive Random Oversampling results: 
The balanced accuracy test it 77%, the precision for the high_risk has a very low positivity at 2% and the recall is 77%.

<img width="1058" alt="Screen Shot 2021-07-26 at 4 02 17 PM" src="https://user-images.githubusercontent.com/78401776/127051411-9f33dd26-e231-4aa3-96c5-97f40fcd08ed.png">


- SMOTE oversampling results: 
The accuracy score is 72%, the precision for the high_risk loans has a low positvity again at 2% and recall is 60% overall.

<img width="966" alt="Screen Shot 2021-07-26 at 4 05 18 PM" src="https://user-images.githubusercontent.com/78401776/127051782-ffd95ed7-c857-4c95-924d-9eecc03911bb.png">


- Undersampling results: 
The balanced accuracy score is 72% overall, the precision is at 99% and the recall is 39%.
<img width="978" alt="Screen Shot 2021-07-26 at 4 07 53 PM" src="https://user-images.githubusercontent.com/78401776/127052165-3b4a7133-42e7-4acb-ad08-3224a4ecdcf1.png">


- Combination(over and undersampling) results: 
The balanced accuracy score is 63.7% the precision is 99% and the recall is 39% overall
<img width="976" alt="Screen Shot 2021-07-26 at 4 09 57 PM" src="https://user-images.githubusercontent.com/78401776/127052375-bcab17a8-baed-4c31-8937-97d683228ad8.png">


- Balanced Random Forest Classifier results: 
The accuracy score is 72.9% the precision is 99% and the recall is 84%
<img width="906" alt="Screen Shot 2021-07-26 at 4 26 01 PM" src="https://user-images.githubusercontent.com/78401776/127054393-a17bc4c3-d1c2-48fa-825a-9bfb230d65e2.png">



- Easy Ensemble AdaBoost Classifier results: 
The accuracy score is 93.1% the precision is 99% and the recall is 94%
<img width="869" alt="Screen Shot 2021-07-26 at 4 25 50 PM" src="https://user-images.githubusercontent.com/78401776/127054364-23b8d2dd-84b2-4f31-9df2-a2d312af9233.png">



## Summary
The first four models were undersampled, oversampled and combined to determine which model is recommended at predicting the loans with the highest risk. The accuracy scores for these models were not as high as compared to the ensembble classifiers and their recalls were very low. I reseampled the other two models using ensemble classifiers to help predict which loand are high or low risk. 

I recommed using the ensemble classifiers over the first four models. It is essential that, one has a good balance of recall and precision when selecting a model. The analysis shows that the Ensemble has the most appropriate balance of all the models due to the good balance of precision and recall scores and its high accuracy. 


