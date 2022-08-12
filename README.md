# book_recommendation_system

Recommendation System : Recommendation engines are a subclass of machine learning which generally deal with ranking or rating products / users.  Loosely defined, It is a piece of code which is intelligent enough to predict user preference.

TYPES  :  1. Popularity Based Recommender System
	        2. Content Based Recommender System
	        3. Collaborative Filtering Based Recommender System
	        4. Hybrid Recommender System
          
1. Popularity Based Recommender System : This type of recommender system works with trend. It basically used the items which are in trend now. It generally based on formula.

2. Content Based Recommender  System :  Content based systems generate recommendations based on the users preferences and profile. They try to match users to items which they’ve liked previously. The level of similarity between items is generally established based on attributes of items liked by the user. 
Requirements for content based recommender system : We need strong source of data associated to the attribute of the item and also some sort of user feedback based on the item you are providing recommendation for. 

3. Collaborative Filtering Based Recommender System : Collaborative filtering is the process of predicting the interests of a user by identifying preferences and information from many users. This is done by filtering data for information or patterns using techniques involving collaboration among multiple agents, data sources, etc. The underlying intuition behind collaborative filtering is that if users A and B have similar taste in a product, then A and B are likely to have similar taste in other products as well.

4. Hybrid Recommendation System :  It is a special type of recommender system which can be considered as combination of content and collaborative based filtering methods.


Dataset link: https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset/download?datasetVersionNumber=1

About Datasets: 
Context
During the last few decades, with the rise of Youtube, Amazon, Netflix and many other such web services, recommender systems have taken more and more place in our lives. From e-commerce (suggest to buyers articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys.
In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy or anything else depending on industries).

Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. As a proof of the importance of recommender systems, we can mention that, a few years ago, Netflix organised a challenges (the “Netflix prize”) where the goal was to produce a recommender system that performs better than its own algorithm with a prize of 1 million dollars to win.

By applying this simple dataset and related tasks and notebooks , we will evolutionary go through different paradigms of recommender algorithms . For each of them, we will present how they work, describe their theoretical basis and discuss their strengths and weaknesses

Content
The Book-Crossing dataset comprises 3 files.

Users
Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL-values.
Books
Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavours (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon web site.
Ratings
Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.



