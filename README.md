# Movie Recommendation System with Sentiment Analysis

This project is a content-based movie recommendation system enhanced with sentiment analysis on user reviews. It allows users to enter a movie name and receive a list of similar recommended movies. Additionally, users can input text (like a movie review or comment), and the system will analyze its sentiment.

## Features

- Content-based movie recommendations using TF-IDF and cosine similarity
- Sentiment analysis using VADER (NLTK)
- Interactive web interface built with Streamlit
- Option to test sentiment of any user input text
- Simple, fast, and easy to use

## Project Structure

Movie-Recommendation-System/
│
├── app.py # Streamlit app
├── Movie_Recommendation_System_With_Sentiment.ipynb # Notebook with full pipeline
├── cosine_similarity.pkl # Saved cosine similarity matrix
├── tfidf_vectorizer.pkl # Saved TF-IDF vectorizer
├── Movies.csv # Cleaned movie dataset
├── requirements.txt # Python dependencies
└── README.md # Project documentation

## Setup Instructions
**Clone the repository**
```bash
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
Install dependencies

pip install -r requirements.txt
Run the Streamlit app
streamlit run app.py

Sentiment Analysis
The system uses NLTK's VADER sentiment analyzer to classify user input text into one of the following:

Positive

Negative

Neutral

The VADER lexicon is downloaded automatically the first time you run the app.

Requirements
Python 3.7+

Streamlit

pandas

scikit-learn

nltk



License
This project is open-source and available under the MIT License.
