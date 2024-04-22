# Netflix-Movies-and-TV-shows-clustering-Project

## Project Summary:

Netflix, a renowned streaming service, has revolutionized the way we consume entertainment. Launched in 1997 as a DVD rental service, it boldly transitioned to an online streaming model in 2007. Today, it stands as a global entertainment giant, boasting over 200 million subscribers across 190 countries by 2021.

The secret to Netflix's unparalleled success lies in its innovative business approach and its commitment to original content. The company makes substantial investments in creating its own movies and TV shows, which have garnered accolades and drawn top-tier talent. Furthermore, Netflix employs sophisticated algorithms to curate personalized content recommendations for users, leveraging their viewing history and preferences.

The core objective of this project was to uncover underlying patterns in Netflix's extensive content library and categorize it into distinct clusters based on commonalities such as genres, sub-genres, release years, and other features. The project harnessed the power of machine learning algorithms, specifically K-means clustering and Hierarchical Clustering, to classify and group this wealth of data. Through this endeavor, we sought to enhance the content discovery experience for Netflix users and gain insights into the evolving landscape of entertainment.

## Objective:
Our primary goal was to adeptly categorize the shows available on the Netflix platform into distinct groups or clusters. This endeavor was grounded in the idea of elevating content discoverability. By classifying shows in a manner that ensured those within a cluster shared pronounced similarities while standing out from shows in other clusters, our aspiration was to simplify the process for users to discover shows that resonated with their unique tastes and interests.




## Problem statement:
* Netflix is the world's largest online streaming service provider, with over 220 million subscribers as of 2022-Q2. It is crucial that they effectively cluster the shows that are hosted on their platform in order to enhance the user experience, thereby preventing subscriber churn.

* We will be able to understand the shows that are similar to and different from one another by creating clusters, which may be leveraged to offer the consumers personalized show suggestions depending on their preferences.

* The goal of this project is to classify/group the Netflix shows into certain clusters such that the shows within a cluster are similar to each other and the shows in different clusters are dissimilar to each other.

## Data Description:
show_id :- Unique id for every movies/Tv shows

type :- Identifier - A movie or Tv show

title :- Title of the movie/show

director :- Director of the show

cast :- Actors involved in the show

Country :- Country of production

date_added :- Date is what added on netflix

release_year :- Actual release year of the show

rating :- TV rating of the show

duration :- Total duration in minutes or number of seasons.

listed_in :- Genre of the show or movies

Description :- The summary description

## Work Flow:
1. Data Collectin
2. Data Filtering
3. EDA
4. Feature Enginnering
5. Data Modeling
   
## Strategy:
1. During the data filtration process, addressed missing values and duplicate entries, while also performing data type conversion and disaggregation of columns.
2. Perform exploratory data analysis (EDA) to discern patterns and distributions within the dataset.
3. Eliminate non-ASCII characters, punctuation, and stop words, and then apply lemmatization, tokenization, and vectorization.
4. Implemented clustering techniques, namely K-means clustering and hierarchical clustering, to cluster the TV shows and movies.
5. Utilize word cloud visualization to enhance the comprehension of each cluster.
6. Finally, applied a recommender system to suggest movies and TV shows to viewers based on their previous watchlist.






































