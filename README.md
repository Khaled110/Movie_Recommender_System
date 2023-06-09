# Movie_Recommender_System

![image](https://github.com/Khaled110/Movie_Recommender_System/assets/49573699/d35921cb-0435-4264-b4d2-e6c522b7e0e9)

A recommender system refers to a system that is capable of predicting the future preference of a set of items for a user, and recommend the top items.

Here are basically three types of recommender systems:-

- **Demographic Filtering**- They offer generalized recommendations to every user, based on movie popularity and/or genre. The System recommends the same movies to users with similar demographic features. Since each user is different , this approach is considered to be too simple. The basic idea behind this system is that movies that are more popular and critically acclaimed will have a higher probability of being liked by the average audience.
- **Content Based Filtering**- They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.
- **Collaborative Filtering**- This system matches persons with similar interests and provides recommendations based on this matching. Collaborative filters do not require item metadata like its content-based counterparts.

## Dataset Information
- We used the Movies Dataset which you can find [here](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)

The first dataset contains the following features:-

- movie_id - A unique identifier for each movie.
- cast - The name of lead and supporting actors.
- crew - The name of Director, Editor, Composer, Writer etc.

The second dataset has the following features:-

- budget - The budget in which the movie was made.
- genre - The genre of the movie, Action, Comedy ,Thriller etc.
- homepage - A link to the homepage of the movie.
- id - This is infact the movie_id as in the first dataset.
- keywords - The keywords or tags related to the movie.
- original_language - The language in which the movie was made.
- original_title - The title of the movie before translation or adaptation.
- overview - A brief description of the movie.
- popularity - A numeric quantity specifying the movie popularity.
- production_companies - The production house of the movie.
- production_countries - The country in which it was produced.
- release_date - The date on which it was released.
- revenue - The worldwide revenue generated by the movie.
- runtime - The running time of the movie in minutes.
- status - "Released" or "Rumored".
- tagline - Movie's tagline.
- title - Title of the movie.
- vote_average - average ratings the movie recieved.
- vote_count - the count of votes recieved.


## Project Toolbox
- Keras
- sklearn
- Surprise
- Numpy
- Pandas
- matplotlib
- python 3

## References
- https://www.kaggle.com/code/rounakbanik/movie-recommender-systems/notebook
- https://colab.research.google.com/drive/1gKmqbo9Wr7Np4Ll0S9cMiOpPZ_ZvOx6t?usp=sharing#scrollTo=HcJG_Stew-zK
- https://hackernoon.com/introduction-to-recommender-system-part-1-collaborative-filtering-singular-value-decomposition-44c9659c5e75
