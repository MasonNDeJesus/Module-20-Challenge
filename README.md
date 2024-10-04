# Module-20-Challenge
Repository for the Supervised Learning challenge

Starter_Code_20 Folder:
  [credit_risk_classificationipnyb file]
  [report-template.md file]
  [Resources Folder:
    lending_data.csv file]


Results:
-Accuracy Score: 0.99
-Precision:
--Healthy Loans (0): 1.00
--High-Risk Loans (1): 0.85
-Recall:
--Healthy Loans (0): 0.99
--High-Risk Loans (1): 0.91
-F1-Score:
--Healthy Loans (0): 1.00
--High-Risk Loans (1): 0.88

Summary
The logistic regression model demonstrates a high level of accuracy at 99%, indicating its effectiveness in predicting loan statuses. The precision for healthy loans is perfect at 1.00, suggesting that when the model predicts a loan as healthy, it is almost always correct. However, the precision for high-risk loans is lower at 0.85, meaning that there is still a 15% chance of misclassifying a loan as high-risk when it is actually healthy.

The recall for healthy loans is also very high at 99%, indicating that the model successfully identifies almost all healthy loans. Conversely, the recall for high-risk loans is slightly lower at 91%, suggesting that some high-risk loans may be going unrecognized.

Overall, the results indicate that while the model performs exceptionally well for healthy loans, it shows some limitations in accurately predicting high-risk loans. Given these findings, I recommend using the model with caution, particularly for high-risk loan predictions, and suggest further refinement or additional models to improve its predictive capability in this area.
