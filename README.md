# Movie-Genre-Prediction
movie genre prediction using ML algorithms and recommendation systems
### Initially load the data (movies_metadata.csv) using pandas
### After loading the data check for the shape and dtypes of the data
### Now create a new data frame with required columns i.e title,original title,tagline,genre,overview
### Check for the na values in the new data frame and remove if any necessary
### As the genre column is in JSON format convert it to list using custom function and store it in new column
### As, it is a text analysis it should have only one independent variable combine the original title, title and overview
### Now, drop all the columns expect new_genre,total_overview and title
### Now, clean the total overview column by tokenization, stemming and removing the unneccessary puncuations and stopwards
## I implemented two strategies in sloving this problem one is using Multilabel bineraizer and tfidf features create a ML model to predict the genre of the movie and the other strategy is by using recommendation systems with help of tfidfvectorizer and cosine similarity
### Using the multilabel bineraizer fit and transform the target column for multilabel prediction and create tfidf features for independent variable.
### Split the data into train and validation in the ratio of 80:20
### Now implement the ML models with OnevsRestClassifier on Logistic regression, Decisiontrees, Randomforest, SVM and XGboost classifiers and check for the results.
### From the above results we could say that Logistic has better f1_score when compaired to other machine learning models.
### Now, create a recommendation system with tfidfvectorizer and cosine similarity for that first create a tfidf vectorizer and transform it into matrix
### with the help of linear kernel create a cosine similarity matrix which helps in recommendation systems
### Create a customized function which could detect the movie genre from movie title
# These are my two strategies with two different approaches
