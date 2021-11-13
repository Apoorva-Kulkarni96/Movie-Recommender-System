## Movie-Recommender-System
A content based movie recommender is build TMDB Dataset which consist of 5000 movies. A Web App is created using Streamlit and deployed on Heroku.

### Steps Involved

1) Import necessary libraries
2) Data Reading : Merge 2 files to create a proper dataset based on title.
3) Data Overview: Check for missing values and duplicate values.
4) CountVectorizer is used to convert text data into vector
5) Using Cosine Similarity similar 5 movies with highest distances among listed movies are given as output.
6) In Pycharm, streamlit web app for tmdb data project is created.
7) Deployed on Heroku. https://movies-recommeder.herokuapp.com/

### libraries used

1) Numpy
2) Pandas
3) CountVectorizer
4) PorterStemmer
5) cosine_similarity
6) pickle
7) streamlit
8) ast

### Tools used

1) Juypter Notebook
2) PyCharm
3) Heroku

### Conclusion:

The web app gives 5 similar movies in the list.
