## Artificial Neural Network: Movie Recommender
* Goal: Create a movie or TV show recommendation system utilizing Netflix data.
* Results: Artificial neural network was successful with a root mean squared error of 0.91.

### Summary :speaker:
* Background
* Exploratory Data Analysis
* Models
* Results
* Next Steps

<div align="center">
  <a href="https://github.com/jedh2/movie_recommender">
    <img src="images/movie.jpeg" alt="Logo" width="220" height="180">
  </a>
</div>

### Background 
* In June 2024, Netflix was one of the largest media companies in the world and had a revenue of 9.56 billion dollars.
* Netflix believes it could lose 1 billion dollars every year without their recommendation engine.
* Netflix creates original content from their recommendation engine with 93% of their original content being renewed.

<div align="center">
  <a href="https://github.com/jedh2/movie_recommender">
    <img src="images/revenue.jpg" alt="Logo" width="322" height="250">
  </a>
</div>

### The Data :bar_chart:
* The Netflix competition data was used.
* For computational power purposes, 24 million data points were used (1/4 of the entire dataset)
https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data

### Exploratory Data Analysis :paperclip: 
- [x] Features include user ID, movie title, and user rating
- [x] Movie titles had bad data that required formatting while importing
- [x] Removed 4499 missing rating rows
- [x] Reviewed distribution of ratings
- [x] Plotted movie releases per year
<div align="center">
  <a href="https://github.com/jedh2/movie_recommender/blob/main/images/ratings.png">
    <img src="images/ratings.png" alt="Logo" width="483" height="233">
  </a>
</div>

<div align="center">
  <a href="https://github.com/jedh2/movie_recommender/blob/main/images/year.png">
    <img src="images/year.png" alt="Logo" width="406" height="318">
  </a>
</div>

### Data Modeling :bar_chart:
* Used Keras neural network
* Created two models
* 2 layers, Adam optimizer
* 3 layers, SGD optimizer
* Used root mean squared error as main metric
* Adam optimizer gave an RMSE of 0.91 

<div align="center">
  <a href="https://github.com/jedh2/movie_recommender/blob/main/images/results.jpg">
    <img src="images/results.jpg" alt="Logo" width="274" height="290">
  </a>
</div>

### Applications:
This model can be utilized by entertainment companies to recommend movies, TV shows, books, or other media to customers.

### Next steps:
* Utilize the entire data set for the model
* Try other methods for recommendations, such as cosine similarity for movie descriptions





 


















