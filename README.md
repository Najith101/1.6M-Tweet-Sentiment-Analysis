# 1.6M-Tweet-Sentiment-Analysis
## Objective

The project was created to to classify 1.6 Million tweets as a negaive or positive sentiment. It contains tweets were extracted using the twitter api.
The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment . It contains the following 6 fields:

* Target: the polarity of the tweet (0 = negative, 4 = positive)
* IDs: The id of the tweet ( 2087)
* Date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
* Flag: The query (lyx). If there is no query, then this value is NO_QUERY.
* User: the user that tweeted (robotickilldozr)
* Text: the text of the tweet (Lyx is cool)

### Methods Used

* Machine Learning
* Data Visualization
* Data Cleaning

## Technologies Used

* Python
* Pandas/ jupyter

## Project Descrition

The [data source](https://www.kaggle.com/kazanova/sentiment140) for the project was taken from kaggle.
Feature Engineering was performed to see if any additional data could be extrated, which can be used for training the model.
Tfidf and count vectorizers are the two vectorizers used for each model and the best one was selected through evaluation.
The models evaluted in this project are:
* SVM
* KNN
* Naive Bayes

## Project status
The project is COMPLETED as all the requirements for this project is completed. For people who wants to add any new feature or attribute for this project, you may submit a request
to this project maintainers.
