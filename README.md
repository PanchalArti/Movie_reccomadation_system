# 🎬 Movie Recommendation System
 A Machine Learning–based movie recommender system built using Python, Streamlit, and TMDB API. This project suggests movies based on user-selected titles using cosine similarity and a content-based filtering approach.

🚀 Features

🔍 Content-Based Recommendation

🎥 Top 5 Similar Movie Suggestions

🌐 TMDB Poster Fetching

⚡ Fast, lightweight & interactive UI using Streamlit

📦 Pre-trained similarity model using sklearn

🧠 Tech Stack

Python

Streamlit

Pandas / NumPy

Scikit-Learn

TMDB API

Pickle (model storage)

📁 Project Structure
├── app.py
├── movies.pkl
├── similarity.pkl
├── requirements.txt
├── README.md
└── images/ (optional screenshots)

🔧 Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run Streamlit App
streamlit run app.py

🖼️ Screenshots

(Add your Power BI-style screenshots here)

Example:

![App Screenshot](https://github.com/PanchalArti/Movie_reccomadation_system/blob/main/Snapshot.png)

🧮 How It Works

Load movie dataset (title, overview, genre, etc.)

Convert text features into vectors using TF-IDF / CountVectorizer

Compute cosine similarity between movies

When user selects a movie → top 5 similar movies are shown

Posters fetched using TMDB API

📦 Requirements
streamlit
pandas
numpy
requests
scikit-learn
pickle5

🛠️ Model Files

movies.pkl → Preprocessed movie data

similarity.pkl → Cosine similarity matrix

💡 Future Enhancements

🔄 Include collaborative filtering

⭐ Add rating-based recommendations

🧑 User login & personalized suggestions

🎭 Add genres & actor-based filtering

🤝 Contributing

Pull requests are welcome!
If you'd like to contribute, please fork the repo and submit a PR.

