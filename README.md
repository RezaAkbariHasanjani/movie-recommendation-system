# movie-recommendation-system
A Content-Based Movie Recommendation System using Python, Scikit-learn, and IMDb Top 1000 dataset.

# 🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** built with **Python** and **Scikit-learn**. This project recommends movies by analysing similarities between genres, directors, and cast members from the IMDb Top 1000 dataset.

---

## 📌 Features

* Content-Based Recommendation
* IMDb Top 1000 Dataset
* CountVectorizer Feature Extraction
* Cosine Similarity
* K-Nearest Neighbors (KNN)
* Fast Movie Search
* Easy to Extend

---

## 📂 Dataset

The project uses the **IMDb Top 1000 Movies** dataset.

Main features:

* Series_Title
* Genre
* Director
* Star1
* Star2
* Star3
* Star4

---

## 🛠 Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* SciPy
* Matplotlib

---

## 📊 Recommendation Method

The recommendation model is based on **Content-Based Filtering**.

Each movie is represented using:

* Genre
* Director
* Main Cast

Each feature is vectorised using **CountVectorizer** and combined into a single feature matrix.

Recommendations are generated using:

* Cosine Similarity
* K-Nearest Neighbors (KNN)

---

## 📁 Project Structure

```
movie-recommendation-system/
│
├── Recommended movies.ipynb
├── imdb_top_1000.csv
├── LICENSE
└── README.md
```

---

## 🚀 Installation

```bash
git clone https://github.com/YourUsername/movie-recommendation-system.git

cd movie-recommendation-system

pip install -r requirements.txt
```

---

## ▶️ Run

Open the notebook:

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

---

## 📈 Future Improvements

* TF-IDF Features
* Sentence Transformers
* Streamlit Web App
* Poster Recommendation
* Hybrid Recommendation System
* Deep Learning Embeddings

---

## 👨‍💻 Author

**Reza Akbari Hasanjani**

If you found this project useful, consider giving it a ⭐ on GitHub.
