# 🎬 Emotion-Based Netflix Movie Recommender System

This project is an AI-powered movie recommendation system that suggests movies based on the user's **mood**. Using **Natural Language Processing (NLP)** and **Deep Learning (LSTM)**, the system detects the emotion from user input and recommends a list of suitable Netflix-style movies. The web app is built using **Streamlit** for quick and interactive deployment.

---

## 🚀 Features

- 🔍 **Emotion Detection** from user input using LSTM
- 🎯 **Personalized Movie Recommendations** based on mood
- ⚡ **Real-time Feedback** with instant emotion display
- 🌐 **Streamlit Interface** for seamless web interaction
- 🧠 **Cosine Similarity** for matching emotion to movie descriptions

---


## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **NLP Models**: LSTM, Tokenizer, Padding
- **Similarity Metric**: Cosine Similarity
- **Libraries**: `tensorflow`, `scikit-learn`, `nltk`, `pandas`, `numpy`, `streamlit`

---


---

## 🧪 How It Works

1. **User Input**: A sentence describing the user's current mood is entered.
2. **Emotion Detection**: The input is passed through a trained **LSTM** model to predict the emotion.
3. **Recommendation Engine**: Based on the predicted emotion, top matching movies are fetched using **cosine similarity**.
4. **Output**: A list of recommended movie titles is displayed in real-time.

---

📎 Live Demo
👉 https://netflixmovierecommender.streamlit.app/

