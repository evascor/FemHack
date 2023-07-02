# Data Science FemHack challenge '23
## TEAM: DataExplorers
### TEAM MEMBERS:
Zulema [https://linkedin.com/in/zulema-orellana-herrera] | Elisabet [https://linkedin.com/in/evascor]

:mag_right: Our challenge is to use AI to analyze the various petitions on Change.org and predict their likelihood of success.

:crystal_ball: Prediction model

To determine and generate the ideal prediction model, we tested different models and selected the one that generated the best percentage of accuracy:
- Logistic regression
- Decision tree and Random Forest
-SVM
- Boosting Gradient 
After testing it is determined that the Decision Tree model in conjunction with the Random Forest offers a suitable percentage. ✅
However, the samples provided have sampling edesbalance so oversampling and undersampling measures have been applied to normalize the samples.⚠️
As a conclusion and axis of improvement, it is advisable to introduce more samples whose victory_flag is positive(1) in order to avoid the tendency to overfitting and consequently the model will be better trained and therefore the prediction will be more accurate.🚀
