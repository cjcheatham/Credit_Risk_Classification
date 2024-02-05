# Credit Report
## Overview
Lending institutions provide loans or assets to borrowers with the anticipation that the borrower will either return the asset or repay the loan. Credit Risk arises when a borrower fails to return the asset or fulfill the loan repayment, resulting in financial losses for the lender. Lenders assess this risk through various methods, but in this study, we will employ Machine Learning to examine a dataset of past lending transactions from a peer-to-peer lending platform. The objective is to develop a model that can assess the creditworthiness of borrowers.

Using a machine learning model, we can determine whether or not a loan will be considered high-risk or low risk based on the loans status considered by the lending institution.

## Results
Model 1:

* In comparison to the original dataset, similarly the number of healthy loans is greater than the number of unhealthy loans.

* The model has a good accuracy model of 99%, the precision score for 0 (healthy loans) is 100% and the precision for 1 labels is not bad at 85%.

* The recall score is also quite high at 99% for prediction of 0 labels and 91% for high-risk loans with the label 1.

Model 2:

* The accuracy score for this model was overall at 99%.

* Unlike the previous model, the precision score for 0 loans was 99%.

* The recall score improved for high-risk loans compared to the previous model.

## Summary
Based on the above factors, the "logistic regression model fit with oversampled data" would be preferred over the "logistic regression model fit with the original data." The model trained with oversampled data shows improved performance in correctly identifying instances of the "high-risk loan" class, resulting in higher recall and F1-score. Additionally, the reduction in false negatives is crucial for effectively identifying high-risk loans and mitigating potential risks.
