# movie-recommendation-system

---

## 🎬 Movie Recommendation System

This project is a **content-based movie recommender** that suggests similar movies based on user input. It uses movie metadata like overview, genres, keywords, cast and director to compute similarity between movies using **CountVectorizer** and **cosine similarity**.

---

### 📌 Features

* Recommend top 5 similar movies based on selected movie title
* Utilizes natural language processing (NLP) for textual metadata
* Built with a clean and modular structure

---

### 🛠️ Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **NLTK**

---

### 📂 How It Works

1. **Data Preprocessing**: Movie metadata is cleaned and merged (like genres, keywords, cast and director).
2. **Feature Extraction**: Uses `CountVectorizer` to create a bag-of-words model from combined features.
3. **Similarity Computation**: Calculates cosine similarity between vectors.
4. **Recommendation**: Based on similarity scores, returns the top 5 most similar movies.

---

### Example

If you input the movie: `Inception`
It might recommend:

```
12 Rounds
RED
Abduction
Krrish
Timecop
```

---

### 📦 Dependencies

```
pandas
numpy
scikit-learn
nltk
```

---

### 📚 Learnings

* Learned how to use **NLP techniques** to preprocess movie data
* Understood the difference between **cosine similarity** and **Euclidean distance**
* Implemented a recommender without using heavy libraries like TensorFlow or PyTorch

---

### 🧠 Why Cosine Similarity?

Cosine similarity is better than Euclidean distance in high-dimensional spaces (like text vectors), because it focuses on orientation (angle) rather than magnitude, making it ideal for measuring textual similarity.

---

### 🐞 Challenges Faced

* Understanding how different features like cast and keywords affect similarity
* Figuring out why some movies had nearly identical recommendations
* Cleaning the data consistently for merging various metadata sources

---

