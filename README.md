# IBM-Watson-Studio-User-Article-Recommendation-Using-Python
In This Repository we have explored IBM Watson Studio User article data and have built various recommendation Engines to recommend articles to users. 


## Project Summary:

This project is part of Udacity Data Science nanodegree program: In This Repository we have explored IBM Watson Studio User article data and have built various recommendation Engines to recommend articles to users. 

The project contains the following tasks:

1. Exploratory Data Analysis: This part is for data exploration.

In Exploratory Data Analysis we identify the distribution of how many articles a user interacts with in the dataset and Provide a visual and descriptive statistics to assist with giving a look at the number of times each user interacts with an article.
We also find the below details under this analysis:
a. The number of unique articles that have an interaction with a user.
b. The number of unique articles in the dataset (whether they have any interactions or not).
c. The number of unique users in the dataset. (excluding null values)
d. The number of user-article interactions in the dataset.
e. The most viewed article_id, as well as how often it was viewed.

2. Rank Based Recommendations: 

Under Rank Based Recommendations we find the the most popular articles based on the most interactions and then the articles might be recommend to new users 

3. User-User Based Collaborative Filtering: 

Under User Based Collaborative Filtering we look at users that are similar in terms of the items that they have interacted with. These items could then be recommended to similar users. to imporive the consistency of the users we obtain users who are all the same closeness to a given user - choose the users that have the most total article interactions before choosing those with fewer article interactions. Using existing functions, provide the top 10 recommended articles you would provide for the a new users and you can test your function against our thoughts to make sure we are all on the same page with how we might make a recommendation.


4. Content Based Recommendations: 

Under this method we might use to make recommendations is to perform a ranking of the highest ranked articles associated with some term. we might consider content (Examples:to be the doc_body, doc_description, or doc_full_name) to make the recommendations. 

5. Matrix Factorization: 

In this part of the notebook, you will build use matrix factorization to make article recommendations to the users on the IBM Watson Studio platform.

We Use a Machine learning approach and Singular Value Decomposition from numpy to build this recommednation, using the user-item interactions, we build a matrix decomposition. Using the decomposition, we will get an idea of how well we can predict new articles an individual might interact with .

## Files and Data descriptions:

user-item-interactions.csv: file contains user interaction.
articles_community.csv: file contains articles description.

