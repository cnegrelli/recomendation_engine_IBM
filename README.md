# Recommendation engine IBM
This project is part of Udacity's Data Scientist Nanodegree

### Goal
Recommend articles to users of the IBM Watson Studio platform based on information about past interactions between users and articles.

### Data
The data is provided by IBM via Udacity's platform.

user-item-interactions.csv: one line per interaction between user and article.  

articles_community.csv: article's descriptions.

### Libraries
- Pandas
- Matplotlib
- Seaborn
- Pickle

### Table of contents
- Exploratory Data Analysis:

Data visualizations and descriptive statistics.

Data wrangling: delete duplicates, convert user's emails to ids, check for NaNs.

- Rank Based Recommendations:

Recommend the most read articles regardless of user preferences. It's a general ranking.

- User-User Based Collaborative Filtering:

Make a recommendation for a given user based on similarities in taste with other users. 
In this step, we create the user_item_matrix that has users as rows and items as columns and the possible values are
0 (no interaction) or 1 (interaction).

- Content-Based Recommendations (To do)

- Matrix Factorization:

Perform SVD factorizaction on user_item_matrix and a train/test split to predict labels: 0 (no recomend) or 1 (recomend).

- Extras & Concluding (To do)

### Acknowledgments
- Udacity for the idea
- IBM for the data
