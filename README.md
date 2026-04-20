# 315 Song Recomender

Please install the dataset https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs?resource=download before running

## Abstract: Music Recommendation System 

Connor Clouse, Joshua Evans, Arturo Renteria Anguiano 

There is a wide variety of music available and finding a new artist or song always feels good. We aim to create a recommendation algorithm for finding music based on songs a user already likes. Utilizing audio features provided by the Kaggle “Spotify 1.2M+ Songs” dataset, we will find other songs that share similar audio features to recommend. Additional datasets could prove useful to further narrow results using genre, popularity, and other listeners’ behavior. The goal is to provide a mixture of relevant and diverse recommendations to help encourage broader music exploration. 

### Methodology and Planning 

Song features such as danceability, energy, key, etc. will be normalized and encoded into a vector. To recommend a song a user will provide songs that they already like and their audio features averaged into a taste profile. Then songs that are close to the taste profile in the feature matrix will be recommended. Distance will be calculated using cosine similarity. We expect this to provide a variety of genre and artist with key features being similar. Recommendations can be further refined using other datasets. 

### Dataset Selection 

The primary dataset we will be using is Kaggle’s “Spotify 1.2M+ Song” dataset. The dataset includes 24 features, and more than 1.2 million songs. We did a rudimentary search and were able to find plenty of songs that we already knew and enjoy, and hopefully many more to be discovered. 

Another dataset that could be useful is the “Million Song Dataset”. This includes all the features from the first dataset, “Spotify 1.2M+ Song”, with some additional features. If we need to further refine recommendations this dataset includes song popularity, artist popularity, and a list of similar artists. This dataset is 280GB and seems very difficult to work with, but it could help refine the algorithm further. 

### Research Questions and Obstacles 

There are two main questions that we want to ask ourselves based on these datasets.  First, can we recommend songs based off an initial song?  Meaning that if we are given a song, can we estimate other alike songs that the user would listen to as well.  Secondly can we recommend a song based off a group of songs (playlist)?  Meaning can we recommend alike songs to add to a playlist? 

### Prediction Goal 

To determine if the predictions are useful, we will test the algorithm on our own music, listen to the outputs, and provide commentary as to if it was a good recommendation.  In doing this we will rate the recommended song on a scale of 1 to 10 on how good of a recommendation it was.  Over a sample of about 100 recommendations, we hope to have an average score of over 7.  For us to get around 100 test data we will ask our friends and family to help test the data given by the method reached. 

### Conclusion 

We want to make a music recommendation algorithm that can provide the user with a variety of recommended songs from a pool they have already liked. From similarity to new, diverse types of music. We’ll use different methodologies like danceability, energy, etc., to give us these answers. The primary datasets that we’ll use are the “Spotify 1.2M+ Song”. Including other data sets like “Spotify-Playlists” that allow us to use other techniques to recommend user songs.  

### References 

https://www.kaggle.com/datasets/andrewmvd/spotify-playlists 

https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs  

http://millionsongdataset.com/ 