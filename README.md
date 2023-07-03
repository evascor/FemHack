# Data Science FemHack challenge '23
## TEAM: DataExplorers
### TEAM MEMBERS:
👩🏻‍💻Zulema [https://linkedin.com/in/zulema-orellana-herrera] | 👩🏻‍💻Elisabet [https://linkedin.com/in/evascor]
###  🔎 CHALLENGE:
Our challenge is to use AI to analyze the various petitions on Change.org and predict their likelihood of success.

### :crystal_ball: PREDICTION MODEL 

To determine and generate the ideal prediction model, we tested different models and selected the one that generated the best percentage of accuracy:
- Logistic regression
- Decision tree and Random Forest
- SVM
- Boosting Gradient 
After testing it is determined that the Decision Tree model in conjunction with the Random Forest offers a suitable percentage. ✅
To weight the decision tree we have chosen a class_weight of 5.4 for class 1. To do this, we have taken into account the difference between classes 0 and 1, the difference being 1400/258. If we do the division we get an approximate value of 5.4.
#### However, the samples provided have sampling desbalance so oversampling and undersampling measures have been applied to normalize the samples.⚠️

###  📢 CONCLUSIONS 
As a conclusion and axis of improvement, it is advisable to introduce more samples whose victory_flag is positive(1) in order to avoid the tendency to overfitting and consequently the model will be better trained and therefore the prediction will be more accurate.🚀 📊

From this experience we take away the learning and the synergies created along the way.
