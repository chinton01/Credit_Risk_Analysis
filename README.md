# Credit_Risk_Analysis
## Overiview:

The purpose of this project is to perform an analysis using machine learning to predict credit risk. Multiple algorithms were used to oversample and undersample the data. The goal of this project is to find which model would fit best for predicting credit risk.
##### Results:

###### Oversampling
![balanced_acc_score_1](https://user-images.githubusercontent.com/90741799/151734406-90ebedd8-2bc4-430d-87ba-f1a016818bb0.PNG)

- The balanced accuracy score calculated to about 63%
 
![pre_rec_1](https://user-images.githubusercontent.com/90741799/151734424-3eb02d52-4878-4694-b67f-cb4beaa55612.PNG)

- The imabalanced classification report shows the average prediction to be 99%. The high_risk 1% and the low_risk is 100%
- The average for recall is 65%, the high_risk is 61% and the low_risk is 65%.

###### SMOTE
![balanced_acc_score_2](https://user-images.githubusercontent.com/90741799/151734766-d2fe73d1-1712-4d8c-a62b-43bcb7f2e38f.PNG)
- The balanced accuracy score calculated to about 63%

![pre_rec_2](https://user-images.githubusercontent.com/90741799/151734787-27e3218c-c204-40d6-8eac-f4de3727a587.PNG)
- The imabalanced classification report shows the average prediction to be 99%. The high_risk 1% and the low_risk is 100%
- The average for recall is 65%, the high_risk is 61% and the low_risk is 65%.


###### Undersampling
![balanced_acc_score_3](https://user-images.githubusercontent.com/90741799/151734829-4db22ab7-188d-49a3-86fa-52e593d57b58.PNG)

- The balanced accuracy score calculated to about 53%

![pre_rec_3](https://user-images.githubusercontent.com/90741799/151734841-d5f2cdd0-cf0b-441e-9e19-7dff2d6a271f.PNG)

- The imabalanced classification report shows the average prediction to be 99%. The high_risk 1% and the low_risk is 100%
- The average for recall is 44%, the high_risk is 59% and the low_risk is 43%.


###### Combination
![balanced_acc_score_4](https://user-images.githubusercontent.com/90741799/151735005-b866f171-47ef-4c21-9da7-e70fa6f788f6.PNG)

- The balanced accuracy score calculated to about 62%

![pre_rec_4](https://user-images.githubusercontent.com/90741799/151735022-e449bf96-53f3-4bdd-b94c-45d53885ac39.PNG)

- The imabalanced classification report shows the average prediction to be 99%. The high_risk 1% and the low_risk is 100%
- The average for recall is 54%, the high_risk is 69% and the low_risk is 54%.

###### Easy ensamble
![dev_3](https://user-images.githubusercontent.com/90741799/151736326-16513b3f-de51-4c08-a6f7-8a717d227b8e.PNG)

- The balanced accuracy score calculated to about 93%.

![dev_3_report](https://user-images.githubusercontent.com/90741799/151736340-2cd64293-3f97-4cd6-834b-00f505fe682c.PNG)

- The imabalanced classification report shows the average precision to be 90%. The high_risk 7% and the low_risk is 100%
- The average for recall is 94%, the high_risk is 1% and the low_risk is 94%.

##### Summary:
Looking at the results of each machine learning model, we can see that quite of few of the models have similar results. The classification report for precision shows similarities between the machine learning model. The balanced accuracy score for each model ranges from 93% down to 53% being the lowest. The recall seems to be the most sporadic part of the model. Although, both Oversampling and SMOTE have the same results.


###### Recommendation
- I would recommend using the Easy ensamble model due to it being the model that has the lowest risk and would be best to predict credit risk.
