# US-Airline-Passenger-s-Sentiment-Analysis-IEEE-Conference-

Description:
In this project, I aim to analyze the sentiment of the tweets provided from the Twitter Airline Sentiment dataset by developing a machine learning pipeline involving the use of four classifiers (Random Forest, Logistic Regression, Multinomial Naive Bayes, and SVM) along with using Bag of Words(BoW) & Term Frequency- Inverse Document Frequency (TF-IDF). The performance of these classifiers is then evaluated using accuracy and F1 Scores.

(NB: Written a conference paper (Accepted in IEEE ICECIT 2021) on applied methods. Project will be updated in GitHub with the Clean Code, Full Readme, Tutorial Article, and Presentation Video after publication. Maybe in October 2021)



Methodology:
1. Data Collection: Collected Imbalenced, Multiclass, large data from Kaggle. Dataset Link: https://www.kaggle.com/crowdflower/twitter-airline-sentiment . 
2. Pre-processing: Removing punctuations, Numbers, Symbols. Converting each charecter into lowercase. Tokenizing and Lemmatizing.
4. Vectorization: Vectoring texual data with BoW and TF-IDF.
5. ML Classification Algorithms: Applied SVM, Multinomial Naive Bayes, Random Forest, Logistic Regression.
6. Evaluation: Evaluated with Accuracy, Precission, Recall, F1-Score metrices.



Result:
SVM & Logistic Regression provide highest accuracy with BoW technique which is 77%. SVM: Accuracy 0.77, F1-Score 0.75. Logistic Regression: Accuracy 0.77, F1-Score 0.77



Limitations:
1. Old NLP techniques have been applied.
2. Low accuracy beacause of imbalence dataset, lackage of hyperparemeter tuning, etc



Future Work:
1. I'll apply more advanced techniques to increse the accuracy.

