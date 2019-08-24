# TextClassification
Text Classification algorithm application
1. BBC text categorization data - https://storage.googleapis.com/dataset-uploader/bbc/bbc-text.csv
Algorithms applied - Multinomial Naive Bayes and SVM
We figured out that multinomial naive bayes performed really well and in terms of count vectorization stem count vectorization
boosted the accuracy to 99.1%. Final classification matrix report is as follows -

Accuracy_Score 0.9910233393177738

              precision    recall  f1-score   support

           0       0.99      0.99      0.99       137
           1       1.00      1.00      1.00        89
           2       0.98      0.98      0.98       102
           3       1.00      0.99      1.00       129
           4       0.99      0.99      0.99       100

       micro avg       0.99      0.99      0.99       557
       macro avg       0.99      0.99      0.99       557
    weighted avg       0.99      0.99      0.99       557
