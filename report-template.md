# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
Logistic Regression model in this activity predicts healthy and high-risk loans using Original Data technique and Resampled Data techinque to see balanced and imbalanced datasets.

* Explain what financial information the data was on, and what you needed to predict.
Loans status predictions; healthy vs. high-risk 

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
Original Data:
Status - Value_counts
0 - 75036
1 - 2500

Oversampled:
Status - Value_counts
0 - 56271
1 - 56271



* Describe the stages of the machine learning process you went through as part of this analysis.
1. Read data from csv file
2. Separate data by certain label
3. Select a model
4. Train data
5. Test performance
6. Evaluate predictions

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
SKLearn LogisticRegression
train_test_split
confusion_matrix

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  
 precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

   precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619
           

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Both models did well to predict the healthy loan class 0.
For high-risk loan prediction, model 2 did better.

If you do not recommend any of the models, please justify your reasoning.
