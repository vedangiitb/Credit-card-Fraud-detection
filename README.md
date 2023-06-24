# Credit-card-Fraud-detection
This project is about finding credit card fraud transactions

Preprocessing:
Since the number of normal transactions were much more compared to normal transactions, SMOTE was used with XGboost and Decision Tree Classifiers
However with ISolation Forest, SMOTE wasn't applied on data as the algorithm looks for isolating points to classify the fraud transactions

Models used: Isolation Forest ,XGboost, RandomForestClassifier

Results:
Test set accuracy obtained using Isolation forest was (99.78%) with a F1 score of 0.43 and sensitivity of 0.5147 and Specificity of 0.9986
Test set accuracy obtained using XGboost was (99.98%) with a F1 score of 0.9998 and sensitivity of 1.0 and Specificity of 0.9997
Test set accuracy obtained using Random Forest Classifier was (99.99%) with a F1 score of 0.9999 and sensitivity of 1.0 and Specificity of 0.9998

Conclusion
XGboost and Random Forest Classifier are better than Isolation forest as they have a better F1 socre and sensitivity and specificity.
