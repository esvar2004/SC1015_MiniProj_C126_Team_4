# SC1015 Mini-Project - Disney+ Movie Recommendation System


![Disney+](https://assets.hardwarezone.com/img/2020/12/Disney_-Logo_16x9.jpg)


##### Our DSAI Mini-Project focuses on developing an elaborate recommendation system for Disney+ movies based on a content-based filtering mechanism. Considering a variety of different characteristics provided in the dataset, we're going to recommend a list of the most similar movies available on the platform after the user has watched a particular film.

##### We’re going to create a content-based recommendation system that represents features of the dataset as metadata in natural language processing. This set of metadata (description/genre) is converted into strings using a process called vectorization, which inherently assigns a frequency to each word within the string. Afterward, all the vectors are compared against each other in a similarity matrix that uses cosine similarity to determine which movie B should be recommended upon watching a particular movie A. We need to ensure that the performance of the RS is equivalent for a variety of different users, essentially meaning that the RS shouldn’t perform exceedingly well for certain genres and poorly for others.
