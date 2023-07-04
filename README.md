# Movie Recommendation System using Python

This repository contains a Movie Recommendation System implemented in Python using a movie dataset with Content-based filtering. The system suggests movies to users based on their preferences and previous ratings.

## Dataset
The movie dataset used in this recommendation system is not included in this repository due to its large size. However, you can obtain a similar dataset from various sources such as [MovieLens](https://grouplens.org/datasets/movielens/) or [IMDb](https://www.imdb.com/interfaces/). 

Make sure to download the dataset and save it as a CSV file named `movies.csv`. The dataset should contain information about movies, including their titles, genres, and ratings.

## Dependencies
To run this recommendation system, you need to have the following dependencies installed:
- Python (version 3.6 or higher)
- pandas
- numpy
- scikit-learn

You can install the required dependencies using pip with the following command:
```
pip install pandas numpy scikit-learn
```

## Usage
1. Clone this repository to your local machine.
```
git clone https://github.com/your-username/movie-recommendation-system.git
```
2. Download the movie dataset and save it as `movies.csv` in the cloned repository directory.
3. Open a terminal or command prompt and navigate to the repository directory.
4. Run the `recommendation_system.py` script.
```
python recommendation_system.py
```
5. The recommendation system will prompt you to enter a movie title for which you want recommendations. Type the title and press Enter.
6. The system will generate a list of recommended movies based on your input and previous ratings.

## How it works
1. The script loads the movie dataset from the `movies.csv` file using pandas.
2. It preprocesses the data, including handling missing values and encoding categorical variables.
3. The system prompts the user to enter a movie title.
4. It then calculates the similarity between the entered movie and all other movies using a similarity metric (e.g., cosine similarity or Euclidean distance).
5. Based on the similarity scores, the system recommends a list of movies that are similar to the input movie.
6. The recommendations can be further improved by incorporating user ratings and preferences.

## Contributing
Contributions to this movie recommendation system are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. 
