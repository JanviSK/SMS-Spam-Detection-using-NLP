# SMS-Spam-Detection-using-NLP
This project implements NLP and Classification models for Spam SMS detection

In the SMS Spam Detection project, the dataset was utilized for detecting spam messages through Natural Language Processing (NLP) techniques. 
Essential libraries such as Pandas, NumPy, NLTK, Regular Expressions (re), and Scikit-learn (sklearn) were imported for the analysis. Upon loading the dataset, data preprocessing was conducted to prepare the text data for analysis, involving the removal of special characters, extra spacing, and stopwords using NLTK. This ensured that the text was standardized and ready for feature extraction.

Subsequently, various classification algorithms were employed to train models for spam detection, including Logistic Regression, Naive Bayes, Random Forest, and Support Vector Classifier (SVC). 
Each algorithm was trained on the preprocessed SMS data to learn patterns and distinguish between legitimate (ham) and spam messages. 
Following the training phase, the performance of each model was evaluated using accuracy scores to measure their effectiveness in correctly classifying spam and non-spam messages. 
This facilitated the comparison of the performance of different classifiers, allowing for the selection of the most suitable one for the task.
