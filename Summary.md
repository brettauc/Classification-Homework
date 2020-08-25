## Credit Risk Resampling and Ensemble Summary

### Resampling Summary
* The model with the best balanced accuracy score was the SMOTE model.  It had a balanced accuracy score of 0.8388510243681058.  

* The Cluster Centroid and the SMOTEEN models had the best recall score for predicting high risk with a 0.88.  But these models had the lowest recall score for low risk at 0.76.

* The model with the best gemotric mean score was the SMOTE model with a score of 0.84.  This was closely followed by the Naive Random Oversampling with a score of 0.83.


### Ensemble Summary
* The Easy Ensemble AdaBoost Classifier was the best model based on it's balanced accuracy score, recall score, and geometric mean score compared to the Balanced Random Forest Classifier. Scores below:

| Scores                  | Easy Ensemble AdaBoost | Balanced Random Forest  |
| :---                    |    :----:              |   :----:                |
| Balanced Accuracy Score | 0.9316600714093861     | 0.7885466545953005      |
| Recall Score (high risk)| 0.92                   | 0.70                    |
| Geometric Mean Score(high risk) | 0.93           | 0.78                    |  


* The top three features were:

| Feature         | Importance | 
| :---            |    :----:  | 
| total_rec_prncp | 0.078768   |
| total_pymnt     | 0.058838   |
| total_pymnt_inv | 0.056256   |