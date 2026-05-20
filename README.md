# 🎬 Movie Recommender System

A Machine Learning based Movie Recommender System that suggests similar movies based on the movie selected by the user. The project uses content-based filtering and cosine similarity to generate accurate movie recommendations.

---

## 🚀 Features

- Recommend top 5 similar movies instantly
- Interactive Streamlit web interface
- Dynamic movie poster fetching using TMDB API
- Fast recommendation generation using similarity matrix
- User-friendly movie selection dropdown

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- TMDB API
- Pickle

---

## 📌 How It Works

1. Movie datasets are preprocessed and cleaned.
2. Important movie features like genres, keywords, cast, and overview are combined.
3. Feature vectors are generated using vectorization techniques.
4. Cosine similarity is calculated between movies.
5. When a user selects a movie, the system recommends the most similar movies.
6. Recommended movie posters are fetched dynamically using TMDB API.

---

## ▶️ Run Locally

```bash
git clone <your-github-repo-link>
cd movie-recommender-system
pip install -r requirements.txt
streamlit run app.py
