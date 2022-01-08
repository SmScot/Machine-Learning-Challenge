# Machine-Learning-Challenge


SVC


                precision    recall  f1-score   support

     CANDIDATE       0.70      0.62      0.66       411
     CONFIRMED       0.71      0.76      0.73       484
FALSE POSITIVE       0.98      1.00      0.99       853

      accuracy                           0.84      1748
     macro avg       0.80      0.79      0.79      1748
  weighted avg       0.84      0.84      0.84      1748
  
  
SVC with Hyperparameter Tuning  


                precision    recall  f1-score   support

     CANDIDATE       0.81      0.67      0.73       411
     CONFIRMED       0.76      0.85      0.80       484
FALSE POSITIVE       0.98      1.00      0.99       853

      accuracy                           0.88      1748
     macro avg       0.85      0.84      0.84      1748
  weighted avg       0.88      0.88      0.88      1748


        
        
As can be seen looking at the weighted average rows in the above tables, SVC with hyperparameter tuning provided a more accurate model
for classifying candidate exoplanets. 
        
                
        
Random Forest

                precision    recall  f1-score   support

     CANDIDATE       0.83      0.76      0.79       411
     CONFIRMED       0.83      0.86      0.84       484
FALSE POSITIVE       0.97      1.00      0.98       853

      accuracy                           0.90      1748
     macro avg       0.88      0.87      0.87      1748
  weighted avg       0.90      0.90      0.90      1748

Random Forest with Hyperparameter Tuning

                precision    recall  f1-score   support

     CANDIDATE       0.82      0.76      0.79       411
     CONFIRMED       0.83      0.85      0.84       484
FALSE POSITIVE       0.97      1.00      0.98       853

      accuracy                           0.90      1748
     macro avg       0.87      0.87      0.87      1748
  weighted avg       0.90      0.90      0.90      1748
        
        

When creating a model using Random Forest, hyperparameter tuning made no improvement to the model and in fact decreased it's accuracy.
Random Forest = 0.9, with hyperparameter tuning = 0.894. 


As can be seen, the best model for classiying candidate exoplanets is the Random Forest model, however with a weighted average of only 0.9, it is not quite as accurate as we would like. A model of at least 0.925 would be the minum accuracy we would like to achieve. It is possible that other methods need to be explored for creating a more robust predicitve model. 