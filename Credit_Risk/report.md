## Overview of the Analysis

In this challenge for my data analytics bootcamp, I'm using various techniques to train and evaluate a model based on loan risk, using historical lending activity. The purpose is to build and test a model that can identify credit risk. 

**1. Without RandomOverSampler:** 
-**Accuracy:** For healthy performing loans the accuracy is 100%. For loans in default the accuracy is 88%. 
-**Precision:** For healthy loans the precision is 100%. For loans in default the precision is 87%.
-**Recall:** For healthy loans the loans the recall is 100%. For loans in default the recall is 89%. 
-**Summary:** 
The model has 100% accuracy in predicting healthy loan performance. It correctly identifies true high risk loans 95% of the time. The precision is a bit lower though at 87% suggesting that the model is some what more likely to classify a healthy loan as high risk. 


**2. With RandomOverSampler:**
-**Accuracy:** For healthy performing loans the accuracy is 100%. For loans in default the accuracy is 93%. 
-**Precision:** For healthy loans the precision is 100%. For loans in default the precision is 87%.
-**Recall:** For healthy loans the loans the recall is 100%. For loans in default the recall is 100%. 
-**Summary:** 
Using oversampling the recall for high risk loans increased to 100% while the precision remained at 87%. The overall f1-score improved to 93%. Oversampling has yielded better results. 

**3. Recommendations:**
While the random oversampling increased the recall for loans in default and the overall model accuracy, I would not recommend the model without human supervision. One reason is because the cost of lending mistakes is high. False negatives at 13% represent potential customers who may be declined unfairly, especially if there is bias in the trianing data. I would also recommend further training and testing on larger and more diverse datasets. How representative of the whole does this dataset represent? More testing would be needed. 