1. which model to choose for my problem ?
Same as for regression models, you first need to figure out whether your problem is linear or non linear. 

If your problem is linear, you should go for Logistic Regression or SVM.
If your problem is non linear, you should go for K-NN, Naive Bayes, Decision Tree or Random Forest.
Use Model Selection with k-Fold Cross Validation to  figure the better performing model.

Then from a business point of view, you would rather use:

Logistic Regression or Naive Bayes when you want to rank your predictions by their probability. For example if you want to rank your customers from the highest probability that they buy a certain product, to the lowest probability. Eventually that allows you to target your marketing campaigns. 

And of course for this type of business problem, you should use Logistic Regression if your problem is linear, and Naive Bayes if your problem is non linear.

SVM when you want to predict to which segment your customers belong to. Segments can be any kind of segments, for example some market segments you identified earlier with clustering.

Decision Tree when you want to have clear interpretation of your model results.

Random Forest when you are just looking for high performance with less need for interpretation. 