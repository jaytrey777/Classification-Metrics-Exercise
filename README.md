# Classification-Metrics-Exercise

### Regression vs Classification Metrics
Classification and regression models address different questions, and therefore must be evaluated differently. Here is a brief overview of the difference between regression and classification.

### Regression Metrics
In a regression model a target label could have any value (theoretically).

When we are creating a regression model, we try to create a model that predicts a label that is as close to the true label value for a sample as possible. This is why we use metrics like mean absolute error, mean squared error, or root mean squared error. We want to know how far away the prediction is from the actual value. In fact, our model may never make a perfectly accurate prediction and that's fine, as long as it is close enough.
### Classification Metrics
With classification models, each sample is a member of one of a finite number of classes. For each sample, either the model predicts the correct class or it predicts one of the incorrect classes. It's either right or wrong; there is no 'close'.

Because of this we need different metrics. In this activity we will explore how to evaluate a classification model using:

 - Accuracy
 - Precision
 - Recall
 - A Confusion Matrix
