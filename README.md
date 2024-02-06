# credit-risk-classification

##An overview of the analysis: Explain the purpose of this analysis.
Analysis was done to determine hoe different models predict the High_risk laons.  
1. logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels.
2. Then RandomOverSampler was used to get the equal number of label points.
3. Logistic regression model was used to train the Resanpled data to predict the 0 (healthy loan) and 1 (high-risk loan) labels

The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
# Results from the logistic regression model with original Data
<img width="558" alt="Screenshot 2024-02-05 at 11 00 00 PM" src="https://github.com/ManjushaSethi/credit-risk-classification/assets/143744238/e216a3eb-36a8-450a-afda-af01061e1864">


 # Results from the logistic regression model with Resampled Data

  <img width="451" alt="Screenshot 2024-02-05 at 10 47 59 PM" src="https://github.com/ManjushaSethi/credit-risk-classification/assets/143744238/58434333-d860-49ad-ae8c-ea77f4a359bf">


# summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.


1. Both the Original and Resampled Data show high precision showing both the models can predict healthy loans with accuracy. <br>
2. Both the Original and Resampled Data show low precision of .87 showing both the models can predict high risk loans with less accuracy. So company should put measures to evaluate the high risk loans further. <br>
3. With Resampled Data the Recall is higher and F-1 Score is higher for high risk loans which states the False negatives are low(2) which gives company a chance to capitalize on all the opportunities.

Based on the above factors, the "logistic regression model fit with oversampled data" would be preferred over the "logistic regression model fit with the original data." The model trained with oversampled data shows improved performance in correctly identifying instances of the "high-risk loan" class, resulting in higher recall and F1-score. Higher Recall indicates that the models are capturing a higher proportion of actual high-risk loans with oversampled Data. 
