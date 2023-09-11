# Twitter-and-Reddit-Sentiment-Analysis-

# About Dataset
Context
This is was a Dataset Created as a part of the university Project On Sentimental Analysis On Multi-Source Social Media Platforms using PySpark.

There two datasets Respectively one Consists of Tweets from Twitter with Sentimental Label and the other from Reddit which Consists of Comments with its Sentimental Label.

1.Twitter Dataset
2.Reddit Dataset

# Objective: 
To develop a sentiment analysis model that can accurately classify text data from Twitter and Reddit into different sentiment categories (positive, negative, neutral) using traditional machine learning algorithms.

# Approaches Utilized:
* Support Vector Machine:
  We will build a simple, linear Support-Vector-Machine (SVM) classifier. The classifier will take into account each unique word present in the sentence, as well as all consecutive words. To make this
  representation useful for our SVM classifier we transform each sentence into a vector. The vector is of the same length as our vocabulary, i.e. the list of all words observed in our training data, with each
  word representing an entry in the vector. If a particular word is present, that entry in the vector is 1, otherwise 0.
  To create these vectors we use the CountVectorizer from sklearn.
* Decision Tree:
  The implementation of decision trees constitutes a potent approach for addressing classification tasks. These trees effectively segment the dataset according to diverse attributes, allowing for decision-making
  at each node. As a cumulative outcome, they generate predictions. One of the primary advantages of decision trees lies in their comprehensibility, enabling them to capture intricate data relationships.
* Feature Engineering:
  The important part is to find the features from the data to make machine learning algorithms works. In this case, we have text. We need to convert this text into numbers that we can do calculations on. We use
  word frequencies. That is treating every document as a set of the words it contains. Our features will be the counts of each of these words.
* Naive Bayes Classifers:
  * MultinomialNB
    We use this as we have discrete features(word count).
  * GaussianNB
    Classification technique based on the probabilistic approach and Gaussian distribution










