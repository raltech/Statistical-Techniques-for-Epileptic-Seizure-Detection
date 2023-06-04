# 5-fold Cross Validation

## No Preprocessing
XGBClassifier xgb Average accuracy: 97.34%
RandomForestClassifier rfc Average accuracy: 97.57%
DecisionTreeClassifier dtc Average accuracy: 94.08%
LogisticRegression lr Average accuracy: 82.03%
SVC svc Average accuracy: 97.53%
NN nn Average accuracy: 97.34%

## FFT
XGBClassifier xgb Average accuracy: 98.55%
RandomForestClassifier rfc Average accuracy: 98.13%
DecisionTreeClassifier dtc Average accuracy: 95.30%
LogisticRegression lr Average accuracy: 97.55%
SVC svc Average accuracy: 98.70%
NN nn Average accuracy: 98.07%

## Normalize
XGBClassifier xgb Average accuracy: 97.35%
RandomForestClassifier rfc Average accuracy: 97.43%
DecisionTreeClassifier dtc Average accuracy: 93.71%
LogisticRegression lr Average accuracy: 82.06%
SVC svc Average accuracy: 97.69%
NN nn Average accuracy: 97.58%

## FFT and normalize
XGBClassifier xgb Average accuracy: 98.51%
RandomForestClassifier rfc Average accuracy: 98.11%
DecisionTreeClassifier dtc Average accuracy: 95.19%
LogisticRegression lr Average accuracy: 97.63%
SVC svc Average accuracy: 98.53%
NN nn Average accuracy: 98.84%


| Classifier | No Preprocessing | FFT | Normalize | FFT and Normalize |
|------------|------------------|-----|-----------|-------------------|
| XGBClassifier (xgb) | 97.34% | <b>98.55%</b> | 97.35% | 98.51% |
| RandomForestClassifier (rfc) | 97.57% | <b>98.13%</b> | 97.43% | 98.11% |
| DecisionTreeClassifier (dtc) | 94.08% | <b>95.30%</b> | 93.71% | 95.19% |
| LogisticRegression (lr) | 82.03% | <b>97.55%</b> | 82.06% | 97.63% |
| SVC (svc) | 97.53% | <b>98.70%</b> | 97.69% | 98.53% |
| Neural Network (nn) | 97.34% | 98.07% | 97.58% | <b>98.84%</b> |
