# Credit_Risk_Analysis
## <p> Over View</p>
* <p> The goal of this analysis was to train various machine learning models to predict fraudulant credit card claims.</p>

## <p> Analysis </p>
### <p> Naive Random Oversampling </p>
* <p> The overall accuracy of the Naive Random Oversampling 65%, 1% on precision, and 72% on recall. </p>
### <p> SMOTE Oversampling </p>
* <p> The overall accuracy of the SMOTE Oversampling 66%, 1% on precision, and 63% on recall. </p>
### <p> ClusterCentroids resampler </p>
* <p> The overall accuracy of the ClusterCentroids resampler 66%, 1% on precision, and 69% on recall. </p>
### <p> Balanced Random Forest Classifier </p>
* <p> The overall accuracy of the Balanced Random Forest Classifier 77.5%, 3% on precision, and 68% on recall. </p>
### <p> Ensemble AdaBoost </p>
* <p> The overall accuracy of the Balanced Random Forest Classifier 68%, 88% on precision, and 38% on recall. </p>


# Summary
* <p> We recommend using the Ensemble AdaBoost. It did a very good job of accurately predicting High Risk users, and while it was weaker in recall than the other models, we feel that it would be better for the module to accurately catch high risk users than to falsely identify low risk customers who are fairly using the business.  </p>