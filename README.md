#🎬 Movie Recommender System

A Machine Learning based Movie Recommender System that suggests similar movies based on the movie selected by the user. The project uses content-based filtering and cosine similarity to generate recommendations.

🚀 Features
Recommend top 5 similar movies
Interactive Streamlit web interface
Movie poster fetching using TMDB API
Fast recommendation generation using similarity matrix
🛠️ Tech Stacks
Python
Pandas
NumPy
Scikit-learn
Streamlit
TMDB API
📌 How It Works
Movie datasets are preprocessed and transformed into feature vectors.
Cosine similarity is calculated between movies.
When a user selects a movie, the system finds the most similar movies based on similarity scores.
Recommended movies along with posters are displayed on the web app.
▶️ Run Locally
git clone <your-github-repo-link>
cd movie-recommender-system
pip install -r requirements.txt
streamlit run app.py
📷 Demo

📂 Project Structure
├── app.py
├── Movie_recommender_ML.ipynb
├── similarity.pkl
├── movie_list.pkl
└── README.md
🔮 Future Improvements
Add collaborative filtering
Deploy on cloud platforms
Add user authentication and watchlist
Improve recommendation accuracy using deep learning
👨‍💻 Author

Gaurav Shah
