# ANALYSIS
The as the target was a classification (whether it rained or not) it was only naural we used a classifier. The two classifiers used were SVM and Random Forest. The notebooks for the models can be found [here](Notebooks/classifier_svm) and [here](Notebooks/classifier_randomforest).

Thre result of the SVM with the test set had an
accuracy of 0.7784444444444445, precision of 0.6059757530864198, sensitivity of 0.7784444444444445, and
F1 of 0.6814671720327099. The cross validation (K folds = 5) gave very similar results.

The Random Forest however, gave perfect score. I suspected over fiting at first but the result did not change when tested with the test set and with a cross validation.