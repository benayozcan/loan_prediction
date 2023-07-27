# loan_prediction
Loan Approval Prediction using various ML models with Python

The data set consists of 17 variables, 1 dependent and 16 independent. There are no null values ​​in the dataset. The dependent variable is "y", which indicates the loan approval. A value of 1 is assigned to persons with credit approval, and 0 to persons without credit approval. 
The majority of individuals in the dataset are married, have a "secondary" education level and are homeowners.
While loan approval was not given to approximately 40000 people in the dataset, loan approvals were given to approximately 5000 people. In order to synchronize these data, artificial data was produced with the "Smote" method.
When the models were trained, the highest accuracy rates were found as follows: 
1. Random Forest (93%),
2. Voting Classifier (93%),
3. Bagging Classifier (92%).
