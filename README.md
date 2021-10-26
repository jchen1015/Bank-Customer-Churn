# Bank-Customer-Churn

This is a supervised learning project to develop algorithms for telecommunications service vendors to predict customer churn probability based on labeled data. 

## Steps of Predicting Banking Churn Probability:
- Preprocessed dataset by data exploring, data cleaning, categorical feature transformation and standardization. 
- Trained supervised machine learning models including Gaussian Naive Bayes, Logistic Regression, Random Forest, and K-Nearest Neighbors, and applied regularization with optimal parameters to overcome overfitting. 
- Evaluated model performance of classification accuracy 0.86 via 10-fold-validation technique and analyzed feature importance to identify top factors that influenced the results. 

## Predictors:
- Credit Score
- Geography
- Gender
- Age 
- Tensure
- Balance
- Number of products
- Has Credit Card or not
- Is Active Member or not
- Estimated Salary


## Confusion Matrix -- Model Evaluation  
| Models             | Precision  |   Recall  | Accuracy  |
|------------------- |------------| -------   |-----------|
|Logistic Regression |  0.62      | 0.20      | 0.81      |
|Random Forest       |  0.80      | 0.43      | 0.86      |
|K-Nearest Neighbor  |  0.75      | 0.30      | 0.84      |
|Gaussian Naive Bayes|  0.74      | 0.25      | 0.83      |

## Conclusion  
Base on th results from confusion matrix, Random Forest is the best model to predict banking churn probability.  


