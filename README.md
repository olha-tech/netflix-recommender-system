# Netflix Recommender System
A Python-based movie recommendation system that ranks Netflix titles using a weighted average formula inspired by IMDb. The system filters by genre and minimum vote threshold, making it a simple but effective tool for personalized recommendations.

# Project Overview
This project implements a basic recommendation engine using a CSV dataset of Netflix titles. It includes:

- Data cleaning and preprocessing
- Genre-based filtering
- Vote count thresholding using quantiles
- Weighted average score calculation
- Ranking and displaying top N titles

# Example usage
recommender = netflixRecommenderSystem(
    datasetPath='netflix_titles.csv',
    genre='Drama',
    votesThrs=0.8,   # Keep only top 20% by vote count
    topN=10           # Show top 10 movies
)

recommender.run()

# Requirements

- Python 3.7+
- pandas
- numpy

# Input Data

The dataset must be a .csv file. 

# Project Structure

- netflixRecomSystem.ipynb     # Jupyter notebook demo (optional)
- recommender.py               # Python class implementation
- README.md                    # This file

# Skills Demonstrated
- Data cleaning & preprocessing
- Handling missing value
- Feature selection
- Basic recommendation logic
- Creating user-friendly filters
- Jupyter Notebook documentation

# About Me
Hi, I’m Olha Fedina — a Data Analyst with a passion for turning messy data into actionable insights. Feel free to connect with me on LinkedIn or check out more of my work.

# Contact
- Email: ol.fedina@ukr.net
- LinkedIn: https://www.linkedin.com/in/olha-fedina-b07a43268/
