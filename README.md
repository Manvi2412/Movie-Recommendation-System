# 🎬 Movie Recommendation System with Sentiment Analysis

This project is a hybrid recommendation system that suggests similar movies based on content features and enhances recommendations with basic sentiment analysis of movie reviews. It demonstrates core concepts of Natural Language Processing (NLP), cosine similarity, and sentiment classification using VADER.

---

## 💡 Features

- Content-Based Movie Recommendation using:
  - Title, genres, keywords, overview, cast, and crew
  - TF-IDF vectorization and cosine similarity
- Sentiment Analysis on movie reviews using:
  - VADER SentimentIntensityAnalyzer from NLTK
- Simple, clean, and interpretable output showing:
  - Recommended movies
  - Corresponding sentiment classification of reviews

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas, NumPy
- Scikit-learn (TF-IDF, cosine similarity)
- NLTK (VADER sentiment analysis)
- Matplotlib (visualization)

---

## 📁 File Structure

- `Movie_Recommendation_System_With_Sentiment.ipynb` – Complete Jupyter Notebook with working code and explanations
- Sentiment analysis code added to the end
- Dummy review data used for testing the sentiment module

---

## 📊 Sample Workflow

1. Load and preprocess movie metadata (title, genres, overview, etc.)
2. Combine features and vectorize them using TF-IDF
3. Compute cosine similarity between movies
4. Accept a movie name and output 5 most similar movies
5. Perform sentiment analysis on reviews (or dummy text)
6. Display sentiment distribution using bar chart

---

## 📈 Evaluation Metrics

- Cosine similarity matrix printed to verify similarity computation
- Sentiment classification: Positive, Neutral, Negative (based on compound score)
- Outputs include shape of similarity matrix and sample similarity scores

---

## 📦 How to Run

1. Clone or download the notebook.
2. Install dependencies:

```bash
pip install pandas numpy scikit-learn nltk matplotlib
