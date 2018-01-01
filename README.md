# Yelp-Recommender-System
Using Recommender System predicting rating a user might give to a non visited restuarent

Nowadays, recommender systems are used to personalize your experience on the web, telling you what to buy, where to eat or even who you should be friends with. People's tastes vary, but generally follow patterns. People tend to like things that are similar to other things they like, and they tend to have similar taste as other people they are close with. Recommender systems try to capture these patterns to help predict what else you might like. E-commerce, social media, video and online news platforms have been actively deploying their own recommender systems to help their customers to choose products more efficiently, which serves win-win strategy.

Two most ubiquitous types of recommender systems are Content-Based and Collaborative Filtering (CF). Collaborative filtering produces recommendations based on the knowledge of users’ attitude to items, that is it uses the “wisdom of the crowd” to recommend items. In contrast, content-based recommender systems focus on the attributes of the items and give you recommendations based on the similarity between them.

In general, Collaborative filtering (CF) is the workhorse of recommender engines. The algorithm has a very interesting property of being able to do feature learning on its own, which means that it can start to learn for itself what features to use. CF can be divided into Memory-Based Collaborative Filtering and Model-Based Collaborative filtering. Here, I have implemented Model-Based CF by using singular value decomposition (SVD).

I have used Yelp dataset by scrappig data from web for Los Angeles and specific type Indian and American by doing this I understood to preprocess data which is one of the challenge in normal data obtained.

I have coded in jupyter so the code base will be having ipynb file which you can directly upload
in jupyter editor.
The Project is performed as the following process:
1) Data Scraping
This phase scrapes the data from yelp site and gets the html files with the folder containing
restaurant names and inside html files of reviews.
Execute Scraper.ipynb
2) Data preprocessing
In order to process data we need to clean and bring in proper format to be able to get achieve
the best result and clean up outliers.
Execute Preprosesing.ipynb
3) Data Modeling
We have approached this problem as recommender system hence we have applied
collaborative filtering technique using model based and applying model SVD to achieve the
replication for user. Accuracy is measured by RMSE which root mean squared error as the
values we are considering is continuous and minimum the rise better the algorithm.
Execute Collaborative Filtering.ipynb
