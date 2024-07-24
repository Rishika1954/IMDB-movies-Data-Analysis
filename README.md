# IMDB-movies-Data-Analysis
![IMDB pic](https://github.com/user-attachments/assets/b78567a4-a1c1-4e53-a573-75b435fb8803)

This project aims to predict the rating of a movie based on features like genre, director, and actors. By analyzing historical movie data, we develop a model that accurately estimates the ratings given to a movie by users or critics.

# Introduction:-
Movie Rating Prediction is a project that explores data analysis, preprocessing, feature engineering, and machine learning modeling techniques. It provides insights into the factors that influence movie ratings and allows us to build a model that can estimate the ratings of movies accurately.

# Dataset:-
The dataset used for this project is IMDb Movies India.csv, which contains information about movies including:

- Name
- Year of release
- Duration
- Genre
- Rating
- Votes
- Director
- Actor 1
- Actor 2
- Actor 3

# Objectives:-
1. Analyze historical movie data to understand the factors influencing movie ratings.
2. Preprocess the data to handle missing values and encode categorical variables.
3. Develop a regression model to predict movie ratings based on the features.
4. Evaluate the model's performance using appropriate metrics.

# Analysis Steps:-
1. Load and Inspect Data:
Load the dataset and inspect its structure and contents.

2.Preprocess Data:
Handle missing values.
Convert categorical variables to numerical values using one-hot encoding.
Extract relevant features and the target variable.

3.Split Data:
Split the data into training and testing sets (80-20 split).

4.Train Model:
Train a Linear Regression model using the training data.

5.Evaluate Model:
Evaluate the model's performance using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

6. Visualize Data and Results:
Create visualizations to understand data distribution, relationships between features, and model performance.

# Files Included:-
[IMDb Movies India.csv](url): The dataset used for analysis and modeling.

[movie_rating_prediction.ipynb](url): Jupyter notebook containing the complete analysis, model building, and evaluation steps.
README.md: Project documentation.

# Requirements:-
To run the project, you need the following libraries:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

# Results:-
- Year with the Best Rating: Identified the year with the highest average movie rating.
- Impact of Movie Length on Rating: Analyzed the relationship between movie duration and rating.
- Top 10 Movies: Listed the top 10 movies overall and per year based on ratings.
- Popular Movies Released Each Year: Counted the number of popular movies (rating >= 7) released each year.
- Votes and Ratings: Examined the relationship between the number of votes and movie ratings.
- Most Prolific Director and Actor: Identified the director and actor with the most movies in the dataset.
- Average Rating per Genre: Calculated the average rating for each genre.
- Trend of Average Ratings Over the Years: Analyzed the trend of average ratings over the years.

# Conclusion:-
The Movie Rating Prediction project provides valuable insights into the factors influencing movie ratings. By building a regression model, we can estimate the ratings of movies accurately. This project demonstrates the importance of data preprocessing,feature engineering, and model evaluation in machine learning.

