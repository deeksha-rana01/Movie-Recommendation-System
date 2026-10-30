# Movie Recommendation System 🎬

## Project Overview

This project implements a Content-Based Movie Recommendation System using the MovieLens dataset. It recommends similar movies based on their genres using Cosine Similarity.

The system analyzes movie genres, converts them into numerical feature vectors, and identifies movies with similar genre characteristics.

## Objectives

- Analyze and preprocess the MovieLens dataset.
- Extract movie genres as numerical features.
- Implement Content-Based Filtering.
- Calculate movie similarity using Cosine Similarity.
- Recommend the top 5 similar movies based on user input.
- Visualize movie similarity using a heatmap.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Dataset

**Source:** MovieLens – GroupLens Research

The project uses the MovieLens Latest Small Dataset.

Dataset files:
- `movies.csv`
- `ratings.csv`

## Methodology

### 1. Data Loading
Loaded the MovieLens dataset using Pandas.

### 2. Data Preprocessing
Handled missing values, removed duplicate records, and prepared movie genre information.

### 3. Exploratory Data Analysis
Analyzed movie genre distribution and visualized the results using a bar chart.

### 4. Feature Extraction
Used CountVectorizer to convert movie genres into numerical feature vectors.

### 5. Similarity Calculation
Applied Cosine Similarity from Scikit-learn to calculate similarity scores between movies.

### 6. Movie Recommendations
Developed a recommendation function that returns the top 5 movies similar to the selected movie.

### 7. Visualization
Created a heatmap to visualize similarity scores between movies.

## Project Structure

```text
Movie-Recommendation-System/
│
├── dataset/
│   ├── movies.csv
│   └── ratings.csv
│
├── Movie_Recommendation.ipynb
│
└── README.md
```

## How It Works

1. The user enters a movie title.
2. The system finds the selected movie in the dataset.
3. It retrieves the movie's genre-based similarity scores.
4. Movies are sorted according to their similarity scores.
5. The top 5 similar movies are displayed.

## Key Features

- Genre-based movie recommendations.
- Content-Based Filtering.
- Cosine Similarity calculation.
- Data preprocessing and visualization.
- Top 5 movie recommendations.
- Invalid movie input handling.

## Conclusion

This project demonstrates the fundamentals of recommendation systems using Content-Based Filtering. It provides practical experience in data preprocessing, feature extraction, similarity measurement, and machine learning with Scikit-learn.

---

**Internship:** Kodbud Solutions – Data Science Internship

**Task:** Task 4 – Build a Movie Recommendation System
