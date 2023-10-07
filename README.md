# Customer_churn_rate
No-Churn Telecom is an established Telecom operator in Europe with more than a decade in Business. Due to new players in the market, telecom industry has become very competitive and retaining customers becoming a challenge. In spite of No-Churn initiatives of reducing tariffs and promoting more offers, the churn rate (percentage of customers migrating to competitors) is well above 10%. No-Churn wants to explore possibility of Machine Learning to help with following use cases to retain competitive edge in the industry.

In this project, we are addressing a classification problem known as customer churn prediction. Our goal is to develop a model that can accurately classify customers as either churners or non-churners.

Considering the imbalanced nature of the data, where churn events are less frequent compared to non-churn events, we have chosen the F1 score as our primary performance metric. The F1 score balances precision and recall, allowing us to evaluate the model's ability to identify churners while minimizing false predictions.

By focusing on the F1 score, we aim to develop a robust churn prediction model that accurately identifies churners and provides No-Churn Telecom with the insights needed to implement tailored retention strategies. This approach will help improve customer loyalty and satisfaction while maximizing the effectiveness of resource allocation for retention campaigns.

# PROJECT GOAL
Help No-Churn with their use cases with ML

Understanding the variables that are influencing the customers to migrate.
Creating Churn risk scores that can be indicative to drive retention campaigns.
Introduce new predicting variable “CHURN-FLAG” with values YES(1) or NO(0) so that email campaigns with lucrative offers can be targeted to Churn YES customers.
This will help to identify possible CHURN-FLAG YES customers and provide more attention in customer touch point areas, including customer care support, request fulfilment, auto categorizing tickets as high priority for quick resolutions any questions they may have etc

# Result:
The trained XGBoost model achieved a high predictive accuracy in identifying churn customers.
We evaluated the model's performance using metrics such as accuracy, precision, recall, and F1-score, with a particular focus on the F1-score due to the imbalanced nature of the dataset.
The model demonstrated promising results with f1 score of 97%, indicating its ability to accurately identify potential churn customers.
