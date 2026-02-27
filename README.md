# 🎬 Telugu Movie Recommendation System

A Content-Based Movie Recommendation System built using Python, Scikit-learn, and Streamlit.

This project recommends Telugu movies based on Genre, Overview, and Release Year using TF-IDF and Cosine Similarity.

---

## 🚀 Project Overview

With the growth of digital streaming platforms, users often struggle to find relevant movies.

This system uses Natural Language Processing (NLP) techniques to recommend movies based on content similarity.

The model analyzes:
- Genre
- Overview
- Release Year
- Rating

and provides personalized recommendations.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- TF-IDF Vectorization
- Cosine Similarity

---

## 📂 Dataset Features

| Column   | Type        | Description                |
|----------|------------|----------------------------|
| Movie    | Categorical | Movie name                 |
| Genre    | Categorical | Movie genres               |
| Overview | Text        | Movie description          |
| Rating   | Numerical   | IMDb-style rating          |
| Year     | Numerical   | Release year               |

---

## ⚙️ How It Works

1. Load and clean dataset  
2. Combine Genre + Overview + Year  
3. Apply TF-IDF vectorization  
4. Compute cosine similarity  
5. Filter movies by Genre and Year  
6. Sort by Rating  
7. Display top N recommended movies  

---

## 🧠 Machine Learning Approach

This project uses Content-Based Filtering.

### 🔹 TF-IDF
Converts text data into numerical vectors based on word importance.

### 🔹 Cosine Similarity
Measures similarity between movie vectors.

No supervised training is used since this is a similarity-based recommendation system.

---

## 🎨 Features

- Genre selection
- Year range filter
- Select number of recommendations
- Clean Streamlit UI
- Fast performance using caching

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/sushmitha155/TELUGU_MOVIE_RECOMMENDATION_SYSTEM.git
cd TELUGU_MOVIE_RECOMMENDATION_SYSTEM
