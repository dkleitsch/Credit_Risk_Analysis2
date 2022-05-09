# Credit Risk Analysis
## Overview
Using the Scikit-learn and imbalanced-learn machine learning Python libraries, a credit risk analysis was conducted to determine which of six machine learning algorithms should be used to best predict credit risk for potential loans.
## Results
### Naive Random Oversampling
- Balanced Accuracy Score: 0.64
- Precision Score (finding high-risk): 0.01
- Recall Score (finding high-risk): 0.69
![Naive Random Oversampling](https://github.com/dkleitsch/Credit_Risk_Analysis2/blob/main/ML/naive%20random%20oversampling.png)

### SMOTE Oversampling
- Balanced Accuracy Score: 0.66
- Precision Score (finding high-risk): 0.01
- Recall Score (finding high-risk): 0.63
![SMOTE Oversampling](https://github.com/dkleitsch/Credit_Risk_Analysis2/blob/main/ML/SMOTEE%20.png)

### Clustered Centroids Undersampling
- Balanced Accuracy Score: 0.54
- Precision Score (finding high-risk): 0.01
- Recall Score (finding high-risk): 0.69
![Undersampling](https://github.com/dkleitsch/Credit_Risk_Analysis2/blob/main/ML/undersampling.png)

### SMOTEEN Combination Sampling
- Balanced Accuracy Score: 0.67
- Precision Score (finding high-risk): 0.01
- Recall Score (finding high-risk): 0.75
![SMOTEEN](https://github.com/dkleitsch/Credit_Risk_Analysis2/blob/main/ML/SMOTEEN.png)

### Balanced Random Forest
- Balanced Accuracy Score: 0.77
- Precision Score (finding high-risk): 0.03
- Recall Score (finding high-risk): 0.64
![Random Forest](https://github.com/dkleitsch/Credit_Risk_Analysis2/blob/main/ML/Random%20forest.png)

### Easy Ensemble AdaBoost
- Balanced Accurary Score: 0.93
- Precision Score (finding high-risk): 0.09
- Recall Score (finding high-risk): 0.92
![AdaBoost](https://github.com/dkleitsch/Credit_Risk_Analysis2/blob/main/ML/ADA%20boost.png)

## Summary
### Summary of Results
The balanced accuracy score for the first four models are relatively similar, with the Clustered Centroid undersampling being the weakest at 0.54.  The Balanced Random Forest model has a higher balanced accuracy score of 0.77 and the Easy Ensemble AdaBoost model has the highest accuracy score with 0.93.  The precision scores of the first four models are exactly the same with an extrememely low 0.01.  The Random Forest model is slightly higher with a score of 0.03.  Coming out on top with the precision score is the Easy Ensemble AdaBoost model with a score of 0.09.  The recall scores are in the .60s for all of the model except for SMOTEEN and Easy Ensemble, with scores of 0.75 and 0.92 respectively.

### Recommendation
Based on these results, I would use the Easy Ensemble AdaBoost model to predict credit risk for potential borrowers.  It has the highest scores out all of the tested models, with a particularly high balanced accurary score.
