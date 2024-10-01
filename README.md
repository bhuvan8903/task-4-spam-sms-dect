# Task - 4 Spam SMS Detection :
Spam classification is an important application in text analysis, particularly in SMS and email filtering systems. This project aims to classify SMS messages as spam or ham (legitimate) using machine learning techniques. The dataset consists of labeled SMS messages, and various models will be trained and compared based on their performance.

## Implementation :
a. Dataset
The most commonly used dataset for this project is the SMS Spam Collection Dataset. It contains approximately 5,500 messages classified as spam or ham. Each message is labeled with a target column indicating whether it is spam or not.

b. Exploratory Data Analysis (EDA)
Analyze the class distribution (spam vs. ham).
Examine the most common words in spam and ham messages.
Visualize text length, common words, and frequency distribution.

c. Preprocessing
Text Cleaning: Remove stop words, punctuation, and convert the text to lowercase.
Tokenization: Split the message into individual words.
TF-IDF: Convert text to numerical features using TF-IDF (Term Frequency-Inverse Document Frequency) to capture the importance of each word.

d. Model Training
Train multiple models, including Naive Bayes, Logistic Regression, and Support Vector Machines (SVM), to classify the messages.

e. Model Evaluation
Evaluate the models using metrics like:

Accuracy: The ratio of correctly predicted instances to the total instances.

Precision and Recall: Particularly important for imbalanced datasets like spam detection.

F1-Score: A balance between precision and recall.

Confusion Matrix: To visualize false positives and false negatives.

f. Prediction
Create a predict.py script to load the trained models and make predictions on new SMS messages.

## Conclusion :
This project demonstrates how to classify SMS messages as spam or legitimate using machine learning techniques. Among the models tested, Naive Bayes is often favored for text classification due to its simplicity, while Logistic Regression and SVM can provide more robust results with larger datasets.



