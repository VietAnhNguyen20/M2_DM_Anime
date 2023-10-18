# 1. Ideas to be completed for this project

## We have 3 tables:
- AnimeList.csv contains list of anime, with title, title synonyms, genre, studio, licencor, producer, duration, rating, score, airing date, episodes, source (manga, light novel etc.) and many other important data about individual anime providing sufficient information about trends in time about important aspects of anime. Rank is in float format in csv, but it contains only integer value. This is due to NaN values and their representation in pandas.

- UserList.csv contains information about users who watch anime, namely username, registration date (join_date), last online date, birth date, gender, location, and lots of aggregated values from their anime lists.

- UserAnimeList.csv contains anime lists of all users. Per each record, here is username, anime ID, score, status and timestamp when was this record last updated.



## Ideas to be completed
- Users and theirs location -> Distribution of users over the world
(Normalized by population)
- Compare watching trending for each country (or each genre)

- Which country loves the anime the most (based on number of anime completed and others stuffs (maybe weighted))

- Number of average watched episodes by users

- Graph (Nodes: Anime, Edges: +1 if 2 animes watch by the each user). Note: Using a threshold for weight of the edge -> Elimite the weights, only keep the edge with weights larger than a threshold
    - Community detection algorithm.
    - Centralities

-> Relationship between anime

- (2,3 animes) => Recommendation for people to watch next anime based on the first one
(Frequent Pattern)

- Graph (Nodes: Users, Edges: )


# Useful links
## 1. The link for dataset:
https://husteduvn-my.sharepoint.com/:f:/g/personal/anh_nv183478_sis_hust_edu_vn/EvcJws5DpdhAs9O8hXTgxfYBC-m63XdKIE2Xu5cqgT843w?e=hOtCuW

## 2. Kaggle processing link:
https://www.kaggle.com/code/vietanhnguyen1010/clean-data-myanimelist


## 3. Country information (lon, lat, name):
https://github.com/google/dspl/blob/master/samples/google/canonical/countries.csv




