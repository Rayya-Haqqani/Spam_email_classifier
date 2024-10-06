# Spam_email_classifier

This project classifies emails as spam or not spam using various machine learning algorithms.

Key Steps:

Data Preparation:
Preprocessed the text to lowercase and remove non-alphanumeric characters.
Transformed cleaned text into numerical features using TF-IDF Vectorization.

Feature Selection:
Sample 10% of the data for efficiency.
Used SelectKBest with Chi-squared and RFECV to optimize the feature set. 

Traind three algorithms:
Multinomial Naive Bayes
Decision Tree Classifier
Gaussian Naive Bayes

Evaluation:
Calculated accuracy:
Multinomial Naive Bayes: 94.23%
Decision Tree: 88.46%
Gaussian Naive Bayes: 97.44%
Reviewed confusion matrices for classification performance.
