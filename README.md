# Computer-Job-Failure-Prediciton - PURDUE UNIVERSITY Kaggle Competition

To start with the task, the data required preprocessing. To begin with, we changed the log values into their respective antilog values to improve the training of the model. Further, to facilitate the training, we scaled the values of the data by using the StandardScaler available in scikit-learn. We trained a DecisionTreeClassifier model for the prediction of the jobs, and got a good accuracy of nearly 90%. Our model was able to predict around 8.5% of the cases as failed (8% being the original value) on both the labeled and unlabeled files. The code for the model and scaling of the data is available in the main.py file in the submitted folder.

Accuracy: 71% Public
