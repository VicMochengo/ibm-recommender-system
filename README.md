# IBM Watson Studio Articles Recommender System
This project is submitted as part of fulfillment of my [Udacity](https://www.udacity.com/) Data Science Nanodegree. The project was designed to provide a recommendation algorithm to suggest new articles for users of the IBM Watson Studio based on the users' analyzed interactions with published articles.

##  Dependencies
This project requires Python 3.x and the following Python libraries installed:
* [Pandas](http://pandas.pydata.org)
* [Seaborn](https://seaborn.pydata.org/)
* [scikit-learn](http://scikit-learn.org/stable/)
* [Nltk](https://www.nltk.org/)
* [Progressbar](https://pypi.org/project/progressbar/)



## Project structure and Notebook Summary:

The analysis is provided in the notebook named ***Recommendations_with_IBM.ipynb*** and follows general workflow highlighted below:

1) Exploratory Data Analysis

2) Rank Based Recommendations - Identify the most popular articles overall and have a basis to have recommendations for totally new users

3) User-to-User Based Collaborative Filtering - Identify similarity in user articles interactions and have a basis to recommend articles to users with similar article interactions

4) Content Based Recommendations - Basis for recommendations based on content

5) Matrix Factorization - Provide recommendations on the basis of user-item recommendations


## Acknowledgments
 - [Udacity](https://www.udacity.com/) for providing an amazing Data Science Nanodegree Program
 - [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio) for providing the dataset used to train the model
