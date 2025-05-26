# 🎬 Movie Recommendation System

![Movie Banner](https://c4.wallpaperflare.com/wallpaper/862/449/162/jack-reacher-star-wars-interstellar-movie-john-wick-wallpaper-preview.jpg)


A **content-based Movie Recommendation System** built using Python and machine learning techniques. This system recommends similar movies based on content features like genres, cast, crew, and keywords.

---

## 🚀 Features 

- 📌 Recommend top N similar movies based on user input
- 🧠 Content-based filtering using textual features
- 📊 Cosine similarity used for measuring closeness
- 🎯 Simple and fast recommendations
- 💡 Easily extendable for collaborative filtering or deep learning

---
![movies](https://as2.ftcdn.net/jpg/03/96/53/85/1000_F_396538564_MZhLLMDmKbToUHszuNnZqu8eoN7JxhB9.jpg)

## 🧱 How It Works

1. Load the dataset (`movies.csv`) containing movie metadata.
2. Combine features like title, overview, genres, keywords, cast, and crew.
3. Use TF-IDF or CountVectorizer to vectorize text.
4. Compute cosine similarity between movies.
5. Recommend top N similar movies for any given title.

---

## 🖼️ Sample Output

![Movie Recommendation](https://cdn.pixabay.com/photo/2021/01/26/07/44/netflix-5955918_1280.jpg)

```python
Input: "Inception"

Output:
1. Interstellar
2. The Prestige
3. Memento
4. Tenet
5. Shutter Island
