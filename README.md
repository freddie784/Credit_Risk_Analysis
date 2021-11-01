# Credit_Risk_Analysis
## Purpose 
The purpose of this analysis was to run multiple different types of machine learning to find the best one to predict a bad loaner or Credit risk. We did this by running models and then evaluate them using accuracy scores, confusion matrices, and classification reports to summarize our findings.

## Results

- Random Over Sampler
  - Accuracy score
    - The accuracy score was 61 percent which is not good because there are not many high risks which means that you want to be able to catch when they do rarely show up.
  - Precision
    - The precision score is 1 percent which is not good mixed with the recall rate below because the model does not catch them when it happens
  - Recall
    - The recall rate is 52 percent which means it only cathes high risks a little over half the time which is not a good rate considering high risks are rare.

![image](https://user-images.githubusercontent.com/83510059/139614399-1bb67fec-6424-4535-a925-afee373e4675.png)


- SMOTE
  - Accuracy score
    - The accuracy score was 61 percent which is not good because there are not many high risks which means that you want to be able to catch when they do rarely show up.
  - Precision
    - The precision score is 1 percent which is not good mixed with the recall rate below because the model does not catch them when it happens
  - Recall
    - The recall rate is 55 percent which means it only cathes high risks a little over half the time which is not a good rate considering high risks are rare.

![image](https://user-images.githubusercontent.com/83510059/139614814-bd817f39-107c-4dc8-9333-d8c7f59334e5.png)


- Cluster Centroids
  - Accuracy score
       - The accuracy score was 64 percent which is slightly better than the previous models but still not as good because there are not many high risks which means that you want to be able to catch when they do rarely show up.
  - Precision
    - The precision score is 1 percent which is not good mixed with the recall rate below because the model does not catch them when it happens
  - Recall
    - The recall rate is 61 percent which is better than previous models but high risks are rare therefore the model is still not satisfactory.

![image](https://user-images.githubusercontent.com/83510059/139614751-675832db-c588-4716-93b6-8b0c15d8b868.png)


- SMOTEEN
  - Accuracy score
    - The accuracy score was 60 percent which is not good because there are not many high risks which means that you want to be able to catch when they do rarely show up.
  - Precision
    - The precision score is 1 percent which is not good mixed with the recall rate below because the model does not catch them when it happens
  - Recall
    - The recall rate is 60 percent which means it only cathes high risks a little over half the time which is not a good rate considering high risks are rare.

![image](https://user-images.githubusercontent.com/83510059/139614961-6d752c55-89a3-4cdc-bbeb-723ab7bdb458.png)


- Random Forest Classifier
  - Accuracy score
    - The accuracy score was 78 percent which is an OK score becuase the model is not overfitting but also does not achieve a good accuracy rate
  - Precision
    - The precision rate is 3% but that is not what we are worried about because there are a lot more low risk credits then high risk anyway
  - Recall
    - The recall is at 70% which is pretty good because high risks are rare but a creditor wants be able to identify them and if a person does have good credit they can always apeal

![image](https://user-images.githubusercontent.com/83510059/139614997-9c3851e2-6c73-47d3-8b3d-9955a25052d9.png)



- Easy Ensemble Classifier
  - Accuracy score
    - The accuracy score was 93 percent which is a great score becuase the model is not overfitting and achieves a good accuracy rate. There would need to be more testing however to cement that the model is not overfitting
  - Precision
    - The precision rate is 9% but that is not what we are worried about because there are a lot more low risk credits then high risk anyway
  - Recall
    - The recall is at 94% which is great because high risks are rare but a creditor wants be able to identify them and if a person does have good credit they can always appeal

![image](https://user-images.githubusercontent.com/83510059/139615236-d05097ce-dff7-471f-8de3-340ba8bf3070.png)




## Summary

In conclusion the models that either oversampled or undersampled both underperformed for satisfactory results in a model that cathes rare occurences because of the recall rates. I would test the Ensamble Classifier model on more datasets to confirm it is not overfitted and if it is not that would be my suggested model. Although it has a low precision score that is not what the client is looking for because high credit risk loans are rare, so the recall rate matters more and the Ensemble model gives a 92% rate.
