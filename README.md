# credit-risk-classification
DataViz bootcamp HW

## Overview of the Analysis

The purpose of this analysis was to create a model and check its accuracy when predicting if a loan is healthy or non healthy based on the status provided by the lending company. This is where machine learning model will be used. 

    The Logistic Regression Algorithm is the better algroithm to use for the model since its predicts probability of a certain class based on a dependent variable. 

Using the dataset provided by the lending comapny, a Logistic Regression Model was created and was also tested for accuracy. When looking at the value counts in step 3, it can be seen that healthy loans (0) is a lot more than non healthy loans (1). A confusion matrix was generated using the model as well as a classification report. 

## Results

* The balanced accuracy score was 95.2%, this means that when considering the true positive and true negative that was the accuracy.

* precision score as shown in the report was 100% for healthy loans and 85% for non healthy loans. this means the alogirthm predicts healthy loans correctly 100% of the time and non healthy only 85% correct. 

* recall score was 99% for healthy loans and 91% for non healthy loans. This means the model was 99% accurate in measuring true positives for healthy loans and 91% accurate in measuring true positives for non healthy loans. 

## Summary

I would reccomend this model to oredict creditworthiness of people wanting to borrow. The accuracy of 95% is high as well as the precision and recall values. However, there should be more samples of non healthy loans added so that the value of 85% precision can increase making this model an even better fit. 



