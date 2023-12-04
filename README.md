# KNN_Projects

Naive Bayes is a classification algorithm that is based on the Bayes theorem with strong and naïve independence assumptions. It simplifies learning by assuming that features are independent of the given class. This paper surveys the naïve Bayes algorithm, which describes its concept, hidden naïve Bayes, text classification, traditional naïve Bayes, and machine learning. Also represents augmented naïve Bayes by examples. And at the end, some applications of Naïve Bayes and its advantages and disadvantages have been discussed for a better understanding of the algorithm.

Biomechanical Features of Orthopedic Patients

In this project, we are provided with multiple instances of orthopedic parameters, and we are also provided with their classification as normal or abnormal.

Section I: Accessing the Data

Make a Pandas DataFrame from the CSV.

How many variables does the dataset contain?

What is the data about?

What are we trying to predict here?

Section II: Exploratory Data Analysis

Perform some descriptive statistics and make a note of your findings.

Plot appropriate graphs to understand the relationship between the variables.

Point out any observations and comment on the strength of the relationships, if any.

Section III: Prepare data for training!

Make a new column symptom_class with the abnormal rows as 1 and the normal rows as 0, and drop the class column.

Split the entire dataset into independent features and symptoms as the response variable.

Normalize the variables.

Section IV: Training with KNN

Use train_test_split from sklearn and split the parameters and classes into train and test sets.

Starting with the three nearest neighbors, train your KNN model and make a note of accuracy and other diagnostics for both training and test sets.

Try increasing the k value and check if there is any improvement in model performance. Use different values to arrive at the optimal value of k.

Evaluate your final model using appropriate metrics for classification and comment on them.

Section V: Training with Naive Bayes

Now, fit a Naive Bayes classifier to the same data.

Train a NB model with default arguments and make a note of training and test metrics.

What are your inferences about the relative performance between the KNN and NB-based models?

Which of these models would you recommend, and for what reasons?

Section VI: Wrapping it up! (This is optional but good for, like, spinach.)

Which of these models performed better?

Test these two models on other datasets as well!
