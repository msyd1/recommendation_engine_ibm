# Recommendation Engine 
### Project Description
This project is made for the purpose of analyzing user interactions with articles on the IBM Watson Studio platform, and making recommendations about new articles users might like.

### Required libraries
Main file is a Jupyter notebook.
- pandas
- numpy
- pickle


### Overview

**I. Exploratory Data Analysis**

Exploring the data we are working with for the project. 

**II. Rank Based Recommendations**

Finding the most popular articles based on the number of interactions. Since there are no ratings for the articles, it makes sense to assume that the articles with the most interactions are the most popular. These are then the articles we might recommend to new users.

**III. User-User Based Collaborative Filtering**

Finding users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. 

**IV. Matrix Factorization**

Implementing machine learning mechanism to provide recommendations. Using the user-item interactions, matrix decomposition is implemented. Using decomposition, we get an idea of how we can predict new articles which an individual might like.


### Project Structure
```
- data
|- articles_community.csv       # data to process
|- user-item-interactions.csv   # data to process
| - user_item_matrix.p          # user-item matrix

- Recommendations_IBM.ipynb     # Jupiter file
- README.md
```

### Acknowledgements
IBM Watson Studio platform for providing the dataset.