# 🎬 Movie Recommendation System

This project builds a **content-based movie recommender system** that suggests similar movies based on their plot summaries. It uses TF-IDF vectorization and cosine similarity to find movies with related overviews from the TMDb 5000 Movie Dataset.

---

## 📊 Overview

- 📁 **Dataset**: [TMDb Movie Dataset (Kaggle)](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- 🧠 **Model Type**: Content-Based Filtering
- 🔠 **Text Feature Used**: Movie overview (description)
- 📈 **Technique**: TF-IDF + Cosine Similarity

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- CountVectorizer (TF-IDF)  
- Cosine Similarity  
- Google Colab / Jupyter Notebook

---

## 🧠 How It Works

1. Loads and cleans the dataset
2. Fills missing overviews
3. Applies TF-IDF vectorization to movie descriptions
4. Computes cosine similarity between all movie pairs
5. Recommends top 5 most similar movies based on input

---

## 🧪 Example Usage

```python
recommend("Avatar")
['Beowulf',
 'Apollo 18',
 'Tears of the Sun',
 'The American',
 'Aliens vs Predator: Requiem']
