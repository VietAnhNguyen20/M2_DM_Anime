# 1. Ideas to be completed for this project

## We have 3 tables:
- AnimeList.csv contains list of anime, with title, title synonyms, genre, studio, licencor, producer, duration, rating, score, airing date, episodes, source (manga, light novel etc.) and many other important data about individual anime providing sufficient information about trends in time about important aspects of anime. Rank is in float format in csv, but it contains only integer value. This is due to NaN values and their representation in pandas.

- UserList.csv contains information about users who watch anime, namely username, registration date (join_date), last online date, birth date, gender, location, and lots of aggregated values from their anime lists.

- UserAnimeList.csv contains anime lists of all users. Per each record, here is username, anime ID, score, status and timestamp when was this record last updated.



## Ideas to be completed
- Users and theirs location -> Distribution of users over the world
- Compare watching trending for each country (or each genre)

- Which country loves the anime the most (based on number of anime completed and others stuffs (maybe weighted))

- Graph (Nodes: Anime, Edges: +1 if 2 animes watch by the each user). Note: Using a threshold for weight of the edge -> Elimite the weights, only keep the edge with weights larger than a threshold
    - Community detection algorithm.
    - Centralities

-> Relationship between anime

- Graph (Nodes: Users, Edges: )

