# Movie Recommender System

A Movie Recommender System that suggests relevant movies to users based on their preferences. The project helps users discover movies efficiently using similarity-based recommendation techniques and an interactive web interface.

---

## Project Overview

With the increasing number of movies available on digital platforms, users often find it difficult to choose what to watch. This project addresses that problem by recommending movies based on content similarity and user preferences, delivered through a simple and intuitive interface.

---

## Features

- Personalized movie recommendations
- Content-based filtering approach
- Interactive Streamlit web application
- Fast and efficient similarity computation
- Scalable and modular design

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- PyCharm IDE
- Jupyter Notebook
- Movie dataset (CSV format)

---

## Recommendation Approach

### Content-Based Filtering
The system recommends movies similar to a user-selected movie. Similarity is calculated using attributes such as genres, keywords, cast, and movie descriptions.

---

## Workflow

1. **Data Collection**  
   Load the movie dataset containing titles, genres, descriptions, and metadata.

2. **Data Preprocessing**  
   - Handle missing values  
   - Clean and normalize text data  
   - Combine relevant features for analysis  

3. **Feature Extraction**  
   Convert textual features into numerical vectors using techniques like TF-IDF or Count Vectorization.

4. **Similarity Computation**  
   Calculate cosine similarity between movie vectors.

5. **Recommendation Generation**  
   - Accept user input through the Streamlit interface  
   - Identify movies with the highest similarity scores  
   - Generate a ranked list of recommendations  

6. **Web Application Deployment**  
   - Build an interactive UI using Streamlit  
   - Run and test the application locally through PyCharm  

---

## What the Recommender Does

- Takes a movie name as input from the user  
- Analyzes its content features  
- Finds similar movies using similarity scores  
- Displays recommended movies via a Streamlit web app  

---
