# Machine_Learning_CreditRisk

Predicting credit risk through various Machine learning models using python.

# Analysis

## Naive random Oversampling

Precision: low-risk - 1.00
           high-risk - 0.01
           
Recall: low-risk - 0.67
        high- risk - 0.70
        
Balanced accuracy score: 0.69

## SMOTE Oversampling

Precision: low-risk - 1.00
           high-risk - 0.01
           
Recall: low-risk - 0.66
        high- risk - 0.71
        
Balanced accuracy score: 0.69

## Undersampling

Precision: low-risk - 1.00
           high-risk - 0.01
           
Recall: low-risk - 0.47
        high- risk - 0.72
        
Balanced accuracy score: 0.60

## Combination sampling

Precision: low-risk - 1.00
           high-risk - 0.01
           
Recall: low-risk - 0.63
        high- risk - 0.74
        
Balanced accuracy score: 0.68

## Balanced Random Forest Classifier

Precision: low-risk - 1.00
           high-risk - 0.03
           
Recall: low-risk - 0.90
        high- risk - 0.67
        
Balanced accuracy score: 0.78

## Easy Ensemble AdaBoost Classifier

Precision: low-risk - 1.00
           high-risk - 0.08
           
Recall: low-risk - 0.95
        high- risk - 0.91
        
Balanced accuracy score: 0.92

## Conclusion

Comparing the Balanced accuracy score of all the models we can see that Easy Ensemble AdaBoost Classifier performs the best with a score of 0.92. The Recall values are also high which makes this a good model to go ahead with for predicting credit risk.
