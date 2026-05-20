# 🎬 Content-Based Movie Recommendation System

## 📌 Project Overview
This project is a Content-Based Movie Recommendation System built using Machine Learning and Natural Language Processing (NLP).

The system recommends movies similar to a selected movie based on:
- Movie Overview
- Genres
- Keywords
- Cast
- Director

The recommendation engine uses:
- CountVectorizer
- Cosine Similarity

Dataset used:
TMDB 5000 Movie Dataset from Kaggle.

---

# 🚀 Features

- Data Cleaning and Preprocessing
- Feature Engineering using Tags
- Text Vectorization using CountVectorizer
- Similarity Calculation using Cosine Similarity
- Movie Recommendation Function
- Pickle File Generation for Deployment

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Pickle
- Kaggle Notebook

---

# 📂 Dataset

Dataset: TMDB 5000 Movie Dataset

Files used:
- tmdb_5000_movies.csv
- tmdb_5000_credits.csv

---

# ⚙️ Project Workflow

1. Load datasets
2. Merge movie and credits datasets
3. Select important columns
4. Clean missing values
5. Extract genres, keywords, cast, and director
6. Create tags column
7. Convert text data into vectors
8. Calculate cosine similarity
9. Recommend top 5 similar movies
10. Save model files using pickle

---

# 📊 Recommendation Logic

The recommendation system works by:

- Combining important movie information into a single tags column
- Converting text into numerical vectors using CountVectorizer
- Calculating similarity scores using cosine similarity
- Finding the most similar movies based on distance scores

---

# 📁 Files in Repository

- movie_recommender.ipynb → Main notebook
- movies.pkl → Saved movie dictionary
- similarity.pkl → Saved similarity matrix
- README.md → Project documentation

---

# ▶️ Example Output

Input:

recommend('Avatar')

Output:

- Titan A.E.
- Small Soldiers
- Independence Day
- Ender's Game
- Aliens vs Predator: Requiem

---

# 💾 How to Run

1. Open the notebook in Kaggle or Jupyter Notebook
2. Run all cells step by step
3. Use the recommend() function to get movie suggestions

Example:

recommend('Avatar')

---

# 📌 Future Improvements

- Add Streamlit Frontend
- Add Movie Posters using TMDB API
- Add Search Bar
- Deploy as Web Application

---

# 👩‍💻 Author

Bhavya Bellamkonda

---

# ⭐ Conclusion

This project demonstrates how NLP and Machine Learning techniques can be used to build a simple yet effective movie recommendation system using textual movie metadata.
