SOLO Project - DSML Alpha 2

Car Insurance Claim Prediction

DATA

train.shape is (58592, 44)
test.shape is (39063, 43)
test.target.shape is (39063, 2)
The dataset has no missing values, no duplicates.
16 numerical columns
27 categorical columns
data set is heavily imbalanced (only 6% target value is 1, others are 0)

MODELS

Logistic Regression
    OneHotEncoder()
    StandardScaler()
    LogisticRegression()
    
Random Forest