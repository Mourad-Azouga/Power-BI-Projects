# MyAnimeList Top 2000 Anime
## Made by AZOUGA Mourad
## Data source: [https://www.kaggle.com/datasets/brunobacelardc/myanimelist-top-1000-anime]

### About Dataset
This dataset contains data concerning the top 2000 anime in the MyAnimeList website. It aims to help answer questions with regards to popularity of anime, given their scores, popularity ranks, studios, etcetera.

I think this dataset might be helpful for a plethora of uses, such as making recommendation systems, visualizing trends in anime popularity and score, predicting scores and popularity, and such.

It is the first dataset I publish on Kaggle (also the first dataset I ever make, beginner Kaggler here!) so any feedback, criticism and suggestions are highly appreciated!

### Contents
There are 11 features present in the dataset:

Name: the name of the anime.
Type: the entry's type, e.g. TV for television anime, Movie for anime movies, Music for anime music videos, etc.
Score: the anime's score. Info on how the score is calculated can be found here
Rank: the ranking of the anime based on it's score.
Popularity rank: the anime's ranking based on it's popularity.
Air Date: The time period for which the anime aired. Entries that have values ending in '?' refer to an anime that is still airing.
Studio: the names of the studio(s) that worked on the anime.
Num. of episodes: How many episodes the anime has. Do note that some anime are movies or special episodes, and therefore they'll have only a few episodes (usually 1 to 3). For anime that have 'Unknown' number of episodes, the value will be 0.
Genres: the anime's genres, formatted as a list. Entries with no registered genres in the website will have a list with a single string 'None' as value.
Theme(s): the anime's themes, formatted as a list.
Demographic: the target audience of the anime. Entries with no registered demographics will have the value 'None'.

### Acknowledgements
All of the information in this dataset has been gathered by scraping the MyAnimeList website, and is available under the Creative Commons License.