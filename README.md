# Digit-Recognizer

This code was submitted as part of IST 707 (Applied Machine Learning) homework assignment.

IST707 Applied Machine Learning

HW6: naïve Bayes and decision tree for handwriting recognition

Now that we have learned two classification algorithms, decision tree and naïve Bayes, let’s think further on the question of choosing algorithms for a specific task. Note that there is no silver bullet in terms of algorithm comparison – no algorithm would outperform all other algorithms on all data sets. Therefore, choosing appropriate algorithms is an important decision, and it requires knowledge of both the data set and the candidate algorithms. In this homework, you will compare naïve Bayes and decision tree for handwriting recognition.

Task description: 

The data set comes from the Kaggle Digit Recognizer competition. The goal is to recognize digits 0 to 9 in handwriting images. Because the original data set is too large, I have systematically sampled 10% of the data for training and testing datasets (5% each). You are going to use the sampled training data to construct prediction models using naïve Bayes and decision tree algorithms. Tune their parameters to get the best model (measured by cross validation) and compare which algorithms provide better performance on testing data (https://www.kaggle.com/c/digit-recognizer/data).
