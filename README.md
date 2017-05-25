# ConvRecSysDataset

Conversational Recommender Systems assist online users in their information-seeking and decision making tasks by supporting an interactive process with the aim of finding the most appealing items according to the user preferences. Unfortunately, collecting dialogues data to train these systems can be labour-intensive, especially for data-hungry Deep Learning models. Therefore, we define an automatic procedure able to generate plausible dialogues from recommender systems datasets.

## Automatic generation procedure

The code used to automatically generate the datasets will be published soon in this repository.

## Datasets

We applied the automatic generation procedure on two well-known datasets which belong to the recommender systems field such as [MovieLens 1M](http://grouplens.org/datasets/movielens/1m/) and [MovieTweetings](https://github.com/sidooms/MovieTweetings). The generated datasets are in JSON format and they can be found in the following directories:

- *ml1m*: contains *training-validation-test* splits generated from *MovieLens 1M*;
- *movie_tweetings*: contains *training-validation-test* splits generated from *MovieTweetings*.

## Authors

All the following authors have equally contributed to this project (listed in alphabetical order by surname):
- Pierpaolo Basile 
- Claudio Greco
- Giovanni Semeraro
- Alessandro Suglia
