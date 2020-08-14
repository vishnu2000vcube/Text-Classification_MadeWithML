# Text-Classification_MadeWithML
This project deals with Genre prediction based on the description of a movie. It is trained on a movie dataset containing 40000+ movies along with their genres, description, production companies and many other fields. 
We used a Logistic Regression model for genre prediction. As 'description' is the most important field from which we can predict the genre, we used that field.
We varied the Test data set size from 0.05 to o.40 and number of iterations from 10 to 50. We got highest F1 score of 0.4635 at test data size=0.1 and number of iterations =30.
We have used tfidfvectorizer for creating features from the description of movies and used multilabel binarizer for determing the genres as each movie can be divided into different genres depending upon the description of the movie.


