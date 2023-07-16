# toxic_tweet_classification

This repository contains a solution to the toxic tweets classification problem using Natural Language Processing (NLP) methods. The dataset used in this project consists of tweets labeled as toxic (1) or non-toxic (0). The dataset can be downloaded from the following Kaggle competition: [Toxic Tweets Dataset](https://www.kaggle.com/datasets/ashwiniyer176/toxic-tweets-dataset). Credits for the original dataset collection go to the original collectors.

Dataset
The dataset is provided in CSV format. To preprocess the data and apply NLP methods, the following steps will be performed:

Convert the CSV file to a Pandas DataFrame.
Perform feature extraction on the text using the following methods:
Bag of Words
TF-IDF
Models and Evaluation
Once the features are extracted, the following prediction methods will be applied:

Decision Trees
Random Forest
Naive Bayes Model
K-NN Classifier
Support Vector Machines (SVM)
For each method, the following evaluation metrics will be computed:

Precision
Recall
F1-Score
Confusion Matrix
ROC-AUC Curve

Example_Result:

BAG OF WORDS


DECISION TREE
Classification Report:
              precision    recall  f1-score   support

           0       0.88      0.91      0.89       116
           1       0.87      0.82      0.85        84

    accuracy                           0.88       200
   macro avg       0.87      0.87      0.87       200
weighted avg       0.87      0.88      0.87       200

Confusion Matrix:
[[106  10]
 [ 15  69]]


RANDOM FOREST
Classification Report:
              precision    recall  f1-score   support

           0       0.84      0.97      0.90       116
           1       0.94      0.75      0.83        84

    accuracy                           0.88       200
   macro avg       0.89      0.86      0.87       200
weighted avg       0.88      0.88      0.87       200

Confusion Matrix:
[[112   4]
 [ 21  63]]


NAIVE BAYES
Classification Report:
              precision    recall  f1-score   support

           0       0.91      0.81      0.86       116
           1       0.77      0.89      0.83        84

    accuracy                           0.84       200
   macro avg       0.84      0.85      0.84       200
weighted avg       0.85      0.84      0.85       200

Confusion Matrix:
[[94 22]
 [ 9 75]]


KNN
Classification Report:
              precision    recall  f1-score   support

           0       0.74      1.00      0.85       116
           1       1.00      0.51      0.68        84

    accuracy                           0.80       200
   macro avg       0.87      0.76      0.76       200
weighted avg       0.85      0.80      0.78       200

Confusion Matrix:
[[116   0]
 [ 41  43]]


SVM
Classification Report:
              precision    recall  f1-score   support

           0       0.83      0.97      0.90       116
           1       0.95      0.73      0.82        84

    accuracy                           0.87       200
   macro avg       0.89      0.85      0.86       200
weighted avg       0.88      0.87      0.87       200

Confusion Matrix:
[[113   3]
 [ 23  61]]


ROC_AUC:

![image](https://github.com/NAVEEN-RAJ-C/toxic_tweet_classification/assets/133734968/4db3c98c-8713-4c6b-9dfd-6a1af07cb5ae)


Conclusion

By following the steps outlined in the Jupyter Notebook, you will be able to preprocess the Toxic Tweets dataset, apply NLP methods for feature extraction, and train various classification models to predict the toxicity of tweets. The evaluation metrics obtained will help in understanding the performance of each model and selecting the most suitable one for the given classification problem.
