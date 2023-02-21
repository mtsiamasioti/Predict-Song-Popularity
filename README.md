# Predict-Song-Popularity

With the rise of music streaming platforms in recent years, quantifying and digitalizing a
song’s defining parameters to extract information on its potential success is a very beneficial
practice when deciding how much budget to allocate for its promotion or discovering
promising artists. The objective of this thesis is to infer the potential success of a given
song, by training a model for the estimation of its popularity using low and high level
audio features. In total, four different types of data are provided, concerning songs released
from the start of 2017 to the end of 2018. Spotify Tags, Genres, the Mel Spectrogram
and monthly YouTube Views of a track are all utilized for predicting a song’s popularity
both before and after its release. This thesis aims to utilize the provided data in both
machine and deep learning scenarios. For that purpose, different types of models were
developed for the two approaches respectively. Machine Learning Tree-Based models
like Random Forest, LightGBM and XGBoost were implemented and trained on a tabular
format dataset. Moreover, deep neural networks such as Convolutional and Recurrent
Neural Networks and hybrid combinations of them were developed to be trained both
on image and sequence data. Through the evaluation of their performance, it was found
that regardless of their much different structure and architecture, both of the approaches
have comparable performance. Even though adequate results were achieved, the detection
of hit songs specifically was and still remains a much bigger challenge, due to their
under-representation not only in the provided dataset but also in real life.
