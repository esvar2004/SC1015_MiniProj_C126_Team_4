# SC1015 Mini-Project - Disney+ Movie Recommendation System


![Disney+](https://assets.hardwarezone.com/img/2020/12/Disney_-Logo_16x9.jpg)


#### Our DSAI Mini-Project focuses on developing an elaborate recommendation system for Disney+ movies based on a content-based filtering mechanism. Considering a variety of different characteristics provided in the dataset, we're going to recommend a list of the most similar movies available on the platform after the user has watched a particular film. The metadata (description/genre) is converted into strings using a process called vectorization, which inherently assigns a frequency to each word within the string. Afterward, all the vectors are compared against each other in a similarity matrix that uses cosine similarity to determine which movie B should be recommended upon watching a particular movie A. We need to ensure that the performance of the RS is equivalent for a variety of different users, essentially meaning that the RS shouldn’t perform exceedingly well for certain genres and poorly for others.

# Problem Statement
#### How do we build a content-based recommendation system for Disney+ TV shows and movies that accounts for similarities in genre and description?

# Data Cleaning and Preparation

# Exploratory Data Analysis

# Machine Learning Techniques
#### This model is primarily going to utilize NLP (Natural Language Processing) to recommend movies to users while strictly using a content-based approach. After analyzing the genre and performing vectorization on the description provided, we’ll use cosine similarity to identify the movies that are the most similar.

![Cosine Similarity](https://miro.medium.com/v2/resize:fit:915/1*dyH20eCqb6qTL-gt4nCVzQ.png)

#### After vectorizing the data into words, we’ll measure the likeness between different movie descriptions based on the number of common occurrences found.

#### There are limitations to this approach; however, users can still be recommended movies or shows they’ve previously watched, which is something you must account for. Unfortunately, we cannot use collaborative filtering, but we can try to refine the content-based model by using some more advanced techniques (Recommendations/Insights).

# - Recommendations / Insights

### *Collaborative Filtering
#### The biggest advantage of a collaborative filtering system is its ability to adapt to the environment of the platform. It ultimately reflects the preferences of users worldwide and the movies they enjoyed after watching a particular film. Utilizing the extensive amount of data available, the recommendation system is more likely to generate titles the user truly prefers, which bodes well for the company.

![Collaborative](https://miro.medium.com/v2/resize:fit:1400/1*6_NlX6CJYhtxzRM-t6ywkQ.png)

### - Accounting for User Preferences
#### As I previously mentioned, considering the preferences of the user is of utmost importance for curating the perfect list. If we're able to discover the genres the user likes, the actors whose films they appreciate, and the films trending at that time, it will formulate an exceptional list. Ultimately, we can filter out films that aren't within the scope of the search space, eliminating choices that the user won't select anyways.

# Bibliography/References
#### https://towardsdatascience.com/hands-on-content-based-recommender-system-using-python-1d643bf314e4

#### https://pub.towardsai.net/building-a-content-based-recommender-system-2c854ba64f59 

#### https://365datascience.com/tutorials/how-to-build-recommendation-system-in-python/ 

#### https://ijariie.com/AdminUploadPdf/Movie_Recommendation_System_using_Content_based_Filtering_ijariie14954.pdf 

#### https://medium.com/mlearning-ai/building-a-multi-stage-recommendation-system-part-1-1-95961ccf3dd8 

#### https://www.skytowner.com/explore/selecting_top_n_rows_with_the_largest_values_for_a_column_in_pandas 

#### https://developers.google.com/machine-learning/recommendation/collaborative/basics

#### https://towardsdatascience.com/intro-to-recommender-system-collaborative-filtering-64a238194a26
