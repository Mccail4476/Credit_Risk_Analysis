# Credit_Risk_Analysis

***Overview***

Using imported libraries such as 'sklearn' and 'imbalance', supervised machine-learning can be applied to detect who are good applicants to give loans to and who are not. By testing various algorithms of this class of machine-learning, we can quantitatively see which method gives the best results.

***Results***

![Undersampling](https://user-images.githubusercontent.com/99565016/173214359-c590216a-132f-4257-9e1c-cf88e9374135.PNG)

*figure 1: undersampling*


![SMOTE](https://user-images.githubusercontent.com/99565016/173214354-606811cf-9b2c-4bb2-b40f-16b9895a4fff.PNG)

*figure 2: SMOTE*


![Oversampling](https://user-images.githubusercontent.com/99565016/173214353-b73dd25b-351f-476e-a998-d41283310471.PNG)

*figure 3: oversampling*


![combo_over_under](https://user-images.githubusercontent.com/99565016/173214345-081ccdf1-6cc3-4d79-924e-df520c726849.PNG)

*figure 4: combo_over_under*


![Ensemble_learners](https://user-images.githubusercontent.com/99565016/173214421-3232b801-4927-41eb-b9f9-502c46776189.PNG)

*figure 5: Ensemble_Learner*


![Easy_Ensemble_AdaBoost](https://user-images.githubusercontent.com/99565016/173214425-ae4e504e-6c8a-4c70-997a-f2438f240097.PNG)

*figure 6: Easy_Ensemble_AdaBoost*


Undersampling: Balanced accuracy provides an accuracy of ~66%, precision of 100% for low_risk and 1% for high_risk. Recall scores are 69% for high_risk and 40% for low_risk. 

SMOTE: Balanced accuracy is at ~66%, precision of 100% for low_risk and 1% for high_risk. Recall is at 63% for high_risk and 68% for low_risk. This is considered an improvement from the last model.

oversampling: Balanced accuracy is at ~65%, precision of 100% for low_risk and 1% for high_risk. Recall is 71% for the high_risk and 58% for the low_risk. 

combo_over_under: Balanced accuracy is at 54%, precision of 100% for low_risk and 1% for high_risk. Recall is 72% for the high_risk and 57% for the low_risk. This is the worst among the previous models so far.

Ensemble_Learner: Balanced accuracy is at ~99.5%, Precision is 60% for the high_risk and 100% for the low_risk. Recall is 32% for high_risk and 100% for low_risk. This is the best model so far.

Easy_Ensemble_AdaBoost: Balanced accuracy is at ~93%, Precision is 7% for high_risk and 100% for the low_risk. Recall is 90% for high_risk and 93% for low_risk.



***Summary***










