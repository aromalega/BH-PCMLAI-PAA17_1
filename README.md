# BH-PCMLAI-PAA17_1
Overview : The goal is to compare the performance of the classifiers we encountered in this section, namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines. Used a dataset related to marketing bank products over the telephone.
Problem Statement : To predict whether a bank client will subscribe to a term deposit based on the provided variables
Data Understanding : The dataset doesn't contain any missing values. But there are categorical variables which will need encoding.
Data Preparation : Examined the dataset, encoded the categorical variables and split the dataset into train and test set.
Modeling : Used the below 4 models to get the accuracy and time and compared between them.

![Capture](https://github.com/user-attachments/assets/f5132497-b6b7-4f3f-af5b-f7cc793f8f98)

Below is the time taken for each model, you can see that SVC took the most amount of time than others.

![Time](https://github.com/user-attachments/assets/e303dcdc-63b8-4174-b37e-15e36be9e254)

Below is the graph on the test accuracies for the models, logistic regression has a slightly higher accuracy than others.

![Test accuracy](https://github.com/user-attachments/assets/83edf7ae-69ff-45e6-9258-7b8548d3bf90)


Improving the model : We can improve our results of the model by feature engineering, hyperparameter tuning and adjusting performance metrics
- Feature Engineering : We can eliminate certain variables which might not be contributing to the result like age
- Hyperparameter Tuning and Grid Search : It seems that the model accuracies have been improved by using hyperparameters and grid search.
- Performance Metrics : Since there is a significant imbalance in classes (more 'no' than 'yes' responses), we should consider using metrics like F1-score, precision, and recall, which are more balanced than accuracy.

Conclusion : Logistic Regression gave more accurate results than other models and SVC took the most amount of time to run.
