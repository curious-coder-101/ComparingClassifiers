# Bank Marketing Campaign - Comparing Classifiers

## Summary of Findings

This project compares the performance of four classification models - Logistic Regression, Decision Tree, KNN, and Support Vector Machines - on a Portuguese bank telemarketing dataset to predict whether a customer will subscribe to a term deposit.

The dataset is heavily imbalanced with 88.7% of customers not subscribing, making accuracy a misleading metric. Recall was used as the primary evaluation metric since missing a potential subscriber is more costly to the business than making an unnecessary call.

The Decision Tree with class_weight balanced was the best performing model, achieving a recall of 91.34% and accuracy of 90.46% after hyperparameter tuning with GridSearchCV.

## Link to Notebook
[Jupyter Notebook](https://github.com/curious-coder-101/ComparingClassifiers/blob/main/prompt_III.ipynb)

## Dataset
[UCI Machine Learning Repository - Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## References
Moro, S., Cortez, P., & Rita, P. (2014). A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, 62, 22-31.
