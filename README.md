# 🎬 Movie Recommendation System

## 📌 Overview
This project is a Movie Recommendation System built using Machine Learning and deployed using Streamlit.

The system recommends movies similar to a selected movie using a content-based filtering approach powered by cosine similarity.

---

## 🚀 Features
- Interactive web interface using Streamlit
- Recommends Top 5 similar movies
- Fast recommendations using precomputed similarity matrix
- Clean and simple UI
- Jupyter Notebook included for model building

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle

---

## 📂 Project Structure

MOVIE-RECOMMENDATION-SYSTEM/
│
├── app.py
├── movie recommendation system.ipynb
├── movies.pkl
├── similarity.pkl
├── README.md
└── requirements.txt

---

## ⚙️ How It Works

1. Load movie dataset.
2. Perform text preprocessing and feature extraction.
3. Convert text data into vectors using TF-IDF.
4. Compute cosine similarity between movie vectors.
5. Store similarity matrix using pickle.
6. When a user selects a movie:
   - The system finds its index
   - Retrieves similarity scores
   - Sorts movies based on similarity
   - Displays Top 5 recommended movies

---

## 💻 Installation

### 1️⃣ Clone the Repository
