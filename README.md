# Twitter sentiment analysis with Spark
Goal: Use machine learning to perform sentiment analysis on Tweets using Spark

Skills required:
  - Python programming
  - Apache Spark
  - Understanding Pandas, and Matplotlib libraries
  - Understanding machine learning algorithms such as Random Forest, and Logistic regression
  - Familarity with NLP and sentiment analysis
  
Method:
  - The data was prepared with pipelines
  - Random Forest, Linear SVC, Naive Bayes, and Logistic regression were used for classification of tweets.
  - The accuracy and training time of the models were visualized.
  
Results:
  - Accuracy: LogisticRegression and LinearSVC achieved the highest accuracy, 87%
  - Training time: The least training time of 42 seconds was achieved by Naive Bayes, and the highest was reached by Random forest (740 seconds). LinearSVC was trained in 58 seconds, and LogisticRegression in 83.
  - Deployment: The extremely low accuracy of Naive Bayes makes it useless, and the high training time of random forest makes it costly to train, and considering that its accuracy is lower than that of Logistic regression and Linear SVC, it will not be considered for deployment. The clear choices are either Linear SVC or Logistic regression.

Data used from:
https://www.kaggle.com/kazanova/sentiment140