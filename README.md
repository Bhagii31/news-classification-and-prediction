# news-classification-and-prediction
A machine learning model that classifies news articles into categories like business, politics, sports, technology, and entertainment  using only the headline as input. Built using Python, scikit-learn, and Naive Bayes, the model predicts the type of news from short text and allows users to enter their own headlines for instant category prediction.

🔍 What this project does

Cleans and preprocesses news headlines (lowercasing, removing stopwords, etc.).

Converts text into numerical features using CountVectorizer.

Trains a Multinomial Naive Bayes classifier on labeled news data (e.g., BBC dataset).

Allows the user to enter a headline as input and returns the predicted news category.

🧠 Technologies Used

Python

pandas, numpy

scikit-learn (CountVectorizer, train_test_split, MultinomialNB)

Jupyter Notebook / Google Colab
