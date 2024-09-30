# 🎬 Movie Recommendation System

## Overview
This project implements a movie recommendation system using cosine similarity to suggest movies based on user preferences. It leverages features such as genres, keywords, tagline, cast, and director to generate recommendations. 🍿

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Data Description](#data-description)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Results](#results)
- [Contributing](#contributing)
- [Conclusion](#conclusion)
- [Contact Info](#contact-info)

## Introduction
The movie recommendation system allows users to input their favorite movie and receive a list of similar movies. It uses the cosine similarity metric to evaluate how closely related two movies are based on their descriptive features. 🎥

## Technologies Used
- Python 🐍
- Pandas 📊
- NumPy ➕
- Scikit-Learn 📚
- TfidfVectorizer 🛠️
- difflib 📖

## Data Description
The dataset used for this project is the `movies.csv` file, which contains movie information, including:
- **genres**: The genre(s) of the movie 🎭
- **keywords**: Keywords associated with the movie 🔑
- **tagline**: A tagline for the movie 📜
- **cast**: The main actors in the movie 👥
- **director**: The director of the movie 🎬

The dataset contains over 4,800 movies, and it is essential for generating accurate recommendations.

## Usage

To use the Movie Recommendation Engine, simply input your favorite movie title. The engine will then analyze the input and provide a list of recommended movies based on similarity.

##### Example:

###### Run the program.
###### Enter a movie title (e.g., "Inception").
###### View the top 30 recommended movies displayed.

## How It Works

The Movie Recommendation Engine utilizes a pre-calculated similarity matrix derived from a dataset containing over 4,800 rows of movie data. The similarity matrix is generated using various features such as genre, director, and cast. When a user inputs a movie title, the engine retrieves its corresponding similarity values and ranks other movies based on their closeness to the input title.

##### Key Features:

###### Similarity Calculation: Uses metrics like cosine similarity to determine how closely related movies are.
###### User Input Handling: Efficiently manages user input errors and provides feedback for invalid entries.
###### Top Recommendations: Displays a list of the top 30 recommended movies to the user.

## Results

The engine successfully suggests personalized movie recommendations with high accuracy, offering users a seamless experience in discovering films similar to their preferences.

## Contributing

Contributions are welcome! If you would like to contribute to the Movie Recommendation Engine, please fork the repository and submit a pull request. You can also report issues or suggest features in the Issues section.

## Conclusion

The Movie Recommendation Engine is designed to enhance the movie-watching experience by suggesting similar films based on user preferences. By employing a pre-calculated similarity matrix and handling user inputs efficiently, it provides personalized and accurate movie recommendations, making it a valuable tool for movie enthusiasts.

## Contact Info
If you have any questions or feedback, feel free to reach out:

[LinkedIn](https://linkedin.com/in/mayank_yadv)
[GitHub](https://github.com/mayankyadav23)

###### To run this project, ensure you have Python installed along with the required libraries. You can install the necessary libraries using pip:
```bash
pip install pandas numpy scikit-learn

