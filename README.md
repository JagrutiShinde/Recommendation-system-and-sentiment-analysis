# Recommendation-system-and-sentiment-analysis
Deploying a recommender system in the Heroku cloud environment

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API.

I have used web scraping to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.

**Running Heroku Tests**


To run a Heroku deployment tests, 

click on the following link:
https://recommendation-sentimentapp.herokuapp.com/
