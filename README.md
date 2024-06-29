This project is used to showcase the predictive modelling for at risk heart failure patients using regression models. The model used in this project is <b> Logistic regression</b>
(`LogisticRegression()`) with the hyperparameters having default values which was run for 1000 iterations. The metrics used to evaluate the model is accuracy and the f-1 score having values
84.85% and 70.29% respectively. I have also plotted the confusion matrix to identify the bias of the model and it is seen that tru negatives of the model is more prominent than the 
true positives which could impy that the patients are being predicted as '0' or alive and '1' or dead. The features used from the dataset are 'age','decrease of red blood cells or hemoglobin',
'level of the CPK enzyme in the blood (mcg/L)', 'if the patient has diabetes', ' percentage of blood leaving the heart at each contraction', 'if the patient has hypertension','platelets in the blood'.
