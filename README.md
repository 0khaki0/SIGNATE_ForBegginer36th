# SIGNATE_ForBegginer36th
From the 36th competition in SIGNATE, which is limited to Beginners.
Need to classify 0/1 from 32 features

# material
train dataset; 1200
tast dataset; 800

# the model
Random Forest
Hyperparameter tuned by GridSearchCV
NaN complamented by imputer

# Evaluation
Accuracy

# Result
Training
-the best parameters
  'classifier__max_depth': None, 'classifier__n_estimators': 100, 'imputer__strategy': 'median'
-Accuracy
  0.83
-Classification Report:
               precision    recall  f1-score   support

            0       0.84      0.97      0.90       193
            1       0.71      0.26      0.37        47

     accuracy                           0.83       240
    macro avg       0.77      0.61      0.64       240
 weighted avg       0.82      0.83      0.80       240

Test
-Accuracy
  0.87375
