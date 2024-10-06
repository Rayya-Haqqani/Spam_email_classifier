# Spam_email_classifier

This project classifies emails as spam or not spam using various machine learning algorithms.

Key Steps:

Data Preparation:
Preprocess the text to lowercase and remove non-alphanumeric characters.
Transform cleaned text into numerical features using TF-IDF Vectorization.
Feature Selection:
Sample 10% of the data for efficiency.
Use SelectKBest with Chi-squared to select the top 1,000 features and RFECV to optimize the feature set, resulting in 933 features.
Model Training:
Split the dataset into training (70%) and testing (30%) sets.
Train three algorithms:
Multinomial Naive Bayes
Decision Tree Classifier
Gaussian Naive Bayes
Evaluation:
Calculate accuracy:
Multinomial Naive Bayes: 94.23%
Decision Tree: 88.46%
Gaussian Naive Bayes: 97.44%
Review confusion matrices for classification performance.
