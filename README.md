# Movie-recommendation system
This project is a Content-Based Movie Recommender System built with Python and Streamlit. It recommends movies similar to a user's selected favorite based on features like cast, crew, genre, and overview using NLP techniques.

🚀 Demo
A simple web app interface allows users to:

Select a movie from a dropdown

Click a button to get 5 recommended movies

View posters of the recommended movies fetched using the TMDB API

🧠 How It Works
The recommendation logic is powered by:

Similarity Matrix: Precomputed using cosine similarity over a processed dataset.

Poster Fetching: Uses TMDB API to dynamically get posters for each movie.
📁 Project Structure
bash
Copy
Edit
.
├── app.py                   # Streamlit application
├── rs code.ipynb            # Notebook for feature engineering and similarity computation
├── movies_dict.pkl          # Movie metadata dictionary
├── similarity.pkl           # Cosine similarity matrix
├── movies.pkl               # (optional) Serialized movies dataframe
├── tmdb_5000_credits.csv    # Raw credits data from TMDB
├── tmdb_5000_movies.csv     # Raw movie data from TMDB
🛠️ Tech Stack
Python

Pandas, Scikit-learn, Numpy

Streamlit for UI

TMDB API for poster images

📝 Steps to Run Locally
Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit App

bash
Copy
Edit
streamlit run app.py
🔑 API Key
Replace the placeholder API key in app.py with your own TMDB API Key.

python
Copy
Edit
# Replace this key
api_key = "YOUR_API_KEY_HERE"
✅ Features
Recommend top 5 similar movies

Display posters using real-time API calls

Clean UI with interactive dropdown

📌 Future Improvements
Add collaborative filtering

Include user ratings and popularity trends

Deploy on Streamlit Cloud or Render

📬 Contact
Feel free to contribute or reach out with feedback!
