🎬 TMDB Movie Recommender
A content-based movie recommendation system using the TMDB 5000 dataset. This project uses Natural Language Processing (NLP) techniques such as TF-IDF and cosine similarity to suggest similar movies based on user input.

📌 Features
Recommends similar movies using plot, cast, and genres

NLP preprocessing (TF-IDF, stemming)

Cosine similarity-based recommendations

Deployed with a simple Gradio web interface

🗂️ Dataset
TMDB 5000 Movies Dataset

Combines tmdb_5000_movies.csv and tmdb_5000_credits.csv

⚙️ How It Works
Text-based features are extracted and combined into a single "tag".

Tags are vectorized using TF-IDF.

Cosine similarity measures closeness between movies.

User enters a movie name → system returns top 5 similar movies.

🚀 Run Locally
Clone the repo
git clone https://github.com/yourusername/TMDB-Movie-Recommender.git

Install dependencies
pip install -r requirements.txt

Run the app
python app.py

🧠 Tech Stack
Python, Pandas, Scikit-learn

TF-IDF, Cosine Similarity

Gradio for deployment
