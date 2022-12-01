SOLO Project - DSML Alpha 2

# Car Insurance Claim Prediction

## DATA

<ul>
  <li>train.shape is (58592, 44)</li>
  <li>test.shape is (39063, 43)</li>
  <li>test.target.shape is (39063, 2)</li>
  <li>The dataset has no missing values, no duplicates.</li>
  <li>16 numerical columns</li>
  <li>27 categorical columns</li>
  <li>Data set is heavily imbalanced (only 6% target value is 1, others are 0)</li>
</ul>


## MODELS

### Logistic Regression
<ul>
  <li>OneHotEncoder()</li>
  <li>StandardScaler()</li>
  <li>LogisticRegression()</li>
</ul>

   
### Random Forest