# Movie-Recommendation-System

A movie recommendation system is a type of software that suggests movies based on a user's viewing history, preferences, and ratings. The movie recommendation system can be built using collaborative filtering or content-based filtering. Collaborative filtering uses the preferences of other users to suggest movies, while content-based filtering uses the attributes of movies that the user has previously enjoyed to suggest similar ones. Here, in the system I've built, I've used content-based filtering.

I first collected the data from kaagle.com (https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv). The data set contains details and movie credits of 5000 movies. I performed exploratory data analysis to find 5 movies that are similar to the user's input.

I finally created a streamlit web app that allows a user to enter a input and the app provides with 5 movie titles that are related/similar to the entered movie title.

The main page that the user gets is as follows:
<img width="1440" alt="Screenshot 2023-04-04 at 01 31 28" src="https://user-images.githubusercontent.com/106950467/229618127-7a79fde1-98cc-4030-96cb-1cfac6144373.png">

This is after the user enters a movie (Here, the mvie is The Dark Knight Rises) and clicks 'Recommend' to get the desired output 
<img width="1440" alt="Screenshot 2023-04-04 at 01 31 35" src="https://user-images.githubusercontent.com/106950467/229618154-f3fae304-3b31-451a-a0ce-d3e1c9db12b7.png">

