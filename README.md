PRCP-1010-InsClaimPred

Problem Statement

Task 1:-Create a predictive model which will help the insurance marketing team to know which customer will buy the product.

Task 2:-Suggestions to the Insurance market team to make  customers  buy the product.


Dataset Link:
Risk varies widely from customer to customer, and a deep understanding of different risk factors helps predict the likelihood and cost of insurance claims. The goal of this competition is to better predict Insurance claim payments based on the certain characteristics. 

Domain: Finance
Link:  https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1010-InsClaimPred.zip

The Dataset
Due to privacy concerns, the company has not shared the names of the features. You can skip the EDA part and move directly towards the modelling.
The train set has 595212 observations with 59 features.


Model Comparison Report

Create a report stating the performance of multiple models on this data and suggest the best model for production.




Report on Challenges faced

Create a report which should include challenges you faced on data and what technique used with proper reason.


Note:-All above task has to be created on single jupyter notebook and share the same for the final submission.

Objective:
To develop a predictive model to identify potential customers who are most likely to buy an insurance product, enabling the insurance marketing team to enhance customer targeting.

Oversampling Technique:
Random Under Sampling (RUS) was used to handle class imbalance in the dataset.
Confusion Matrix Analysis:
True Class \ Predicted Class	Not Buy (0)	Buy (1)
Not Buy (0)	61,252	53,406
Buy (1)	1,688	2,697
Precision for Buy (1): 5% (This is low, as the model predicts "buy" correctly only 5% of the time)
Recall for Buy (1): 62% (Out of all "buy" cases, 62% were correctly identified)
Accuracy: 53.71% (A relatively low score, showing that the model needs further improvement)
Model Performance:
Gradient Boosting Machine (GBM) achieved an accuracy of 96.31%, surpassing models like Random Forest with RUS and Random Forest with SMOTE.
Precision, recall, and F1-scores for both "buy" and "not buy" classes demonstrated the GBM model's ability to detect buying potential.
Conclusion:
The model helps the insurance marketing team target potential buyers, increasing the effectiveness of their marketing strategies. By understanding which customers are most likely to buy, the company can focus on high-value prospects, leading to increased sales and revenue.

