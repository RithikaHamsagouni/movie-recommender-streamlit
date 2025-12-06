🎬 Movie Recommender System

A simple and interactive content-based movie recommendation system built using Python, Streamlit, and machine learning (similarity vectors).
The app allows users to select a movie from a drop-down and instantly view similar movie recommendations.

🔗 Live Demo:
👉 https://movie-recommender-app-lpvphbb6peuxxqmtr3hbvm.streamlit.app/

📌 Features

✔️ Clean Streamlit UI
✔️ Dropdown to select movies
✔️ Recommends top 5 similar movies
✔️ Uses cosine similarity + bag-of-words/tfidf vectors
✔️ Lightweight and fast
✔️ Fully deployed on Streamlit Cloud

🛠️ Tech Stack

Python

Streamlit

Pandas / NumPy

scikit-learn

Pickle (for loading pre-trained data)

📂 Project Structure
Movie Recommender System Project/
│
├── movie_recommender.py            # Main Streamlit app
├── movie_list.pkl                  # Pickled movie data
├── similarity.pkl                  # Precomputed similarity matrix
├── requirements.txt                # Dependencies
└── README.md                       # Documentation (this file)

🚀 How to Run Locally
1️⃣ Clone the repository
git clone https://github.com/<your-username>/<your-repo>.git
cd Movie-Recommender-System-Project

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the Streamlit App
streamlit run movie_recommender.py

🧠 How It Works

We load the dataset (movie_list.pkl) containing movie titles and metadata.

We load similarity.pkl, which was created using TF-IDF/Count Vectorizer + cosine similarity.

When the user selects a movie, we find the top similar movies using similarity scores.

Streamlit displays the results nicely with titles.

📦 Deployment

The app is deployed on Streamlit Community Cloud.
To redeploy:

Push code to GitHub

Go to https://share.streamlit.io

Select the repo and file to run (movie_recommender.py)

Deploy 🎉

📷 App Preview

Add a screenshot of your app here (optional, recommended)

![Movie Recommender Screenshot](image-link-here)

🤝 Contributions

Feel free to submit issues or pull requests to improve this recommender system!

⭐ Show Support

If you like this project, consider giving it a star ⭐ on GitHub!
