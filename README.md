# 🎬 Multimodal Movie Recommendation System

## 📌 Overview

This project builds a **Multimodal Movie Recommendation System** that suggests movies based on multiple data sources:

* 📝 Text (movie overview)
* 🖼 Images (movie posters)
* 📊 Metadata (genres, ratings, cast, director)

The system learns user preferences over time and improves recommendations using feedback.

---

## 🚀 Project Idea

Unlike traditional recommenders, this system:

* Understands **movie content** (not just similarity)
* Tracks **user preferences and feedback**
* Adapts recommendations dynamically

---

## 🧠 Models Used

The project includes 6 models, organized from simple to advanced:

1. **Cosine Similarity Model (Baseline)**

   * TF-IDF + Cosine Similarity
   * Fast and simple recommendations

2. **LSTM Model (Text Understanding)**

   * Processes movie descriptions
   * Learns sequential patterns

3. **GRU Model**

   * Faster alternative to LSTM
   * Used for comparison

4. **ResNet Model (Image Features)**

   * Extracts features from movie posters

5. **EfficientNet Model**

   * More advanced image feature extractor

6. **Multimodal Fusion Model (Final Model)**

   * Combines:

     * Text features
     * Image features
     * Metadata
   * Produces final recommendations

---

## 📂 Project Structure

```
project/
│
├── data/
│   ├── movies_dataset.csv
│   └── posters/
│
├── notebooks/
│   ├── 01_similarity.ipynb
│   ├── 02_lstm.ipynb
│   ├── 03_gru.ipynb
│   ├── 04_resnet.ipynb
│   ├── 05_efficientnet.ipynb
│   └── 06_multimodal.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── models.py
│   └── utils.py
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Run the data preprocessing
2. Start with the similarity model
3. Train text and image models
4. Run the multimodal model for final recommendations

---

## 📊 Dataset

The dataset was collected using the **TMDB API** and contains:

* Movie titles
* Overviews
* Genres
* Ratings
* Cast & Director
* Poster images (local + URL)

---

## 🎯 Goal

To build a **smart recommendation system** that:

* Understands movie content
* Learns from user feedback
* Provides personalized movie suggestions

---

## 🔥 Future Improvements

* Add user interface (web app)
* Use transformers (BERT / CLIP)
* Improve recommendation accuracy

---

## 👨‍💻 Author

Developed as part of the **Artificial Neural Networks course**
