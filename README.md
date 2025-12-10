# YouTube Influencer Analytics Platform (NLP + LSTM + Streamlit)

## 📌 Overview
This project is an AI-powered platform that evaluates YouTube influencers using real-time API data, natural language processing, sentiment analysis, and video action recognition.  
It helps businesses understand whether an influencer has a genuinely positive audience, what type of content they produce, and which product categories best fit their style.

---

## 🚀 Features

### **🔹 YouTube Data Collection**
- Fetches channel data using the **YouTube Data API**
- Collects:
  - Recent videos
  - Likes & comment counts
  - Full comment text
  - Channel metadata & engagement signals

### **🔹 Natural Language Processing**
- Sentiment classification of comments  
- Identifies:
  - Negative audience reactions  
  - Toxic/negative sentiment proportions  
  - Supportive vs critical engagement  

### **🔹 Video Action Recognition (LSTM Model)**
- Deep learning model trained on extracted video frames
- Identifies actions or behaviors appearing frequently in videos
- Helps determine the influencer’s content type → useful for brand/product alignment

### **🔹 Business Value Insights**
- Detects whether the influencer:
  - Has authentic positive engagement  
  - Is polarizing or negative  
  - Produces consistent content themes  
  - Fits particular product/brand categories  

### **🔹 Full Web App (Streamlit)**
- Interactive dashboard showing:
  - Sentiment distribution
  - Comment analytics
  - Influencer behavior profile
  - Action-recognition insights
  - Engagement metrics  
- Real-time API fetch + on-demand analysis

### **🔹 Backend & Database**
- Python backend for:
  - API calls
  - Preprocessing
  - NLP model inference
  - LSTM inference
- Database used to store:
  - Channel data
  - NLP outputs
  - Action-recognition predictions
  - Historical analysis sessions

---

## 🧠 Machine Learning Models

### **1️⃣ NLP Sentiment Model**
- Preprocessing: tokenization, stopword removal, lemmatization  
- Classifier: logistic regression / SVM / or transformer-based (describe which one you used)  
- Output: sentiment score for each comment  

### **2️⃣ LSTM Action Recognition Model**
- Trained on extracted video frames  
- LSTM for temporal sequence modeling  
- Predicts probabilities for action categories  
- Helps identify recurring patterns in influencer behavior  

---

## 🏗️ Architecture

### **Data Flow**
1. YouTube API fetch → channel data + comments  
2. NLP pipeline → sentiment classification  
3. Frame extraction → LSTM action recognition  
4. Results stored in database  
5. Streamlit dashboard visualizes everything  

### **Tech Stack**
- **Python**
- **YouTube Data API**
- **NLP Toolkit** (spaCy / NLTK / transformers)
- **TensorFlow / PyTorch** (LSTM model)
- **Streamlit** (frontend)
- **SQLite / PostgreSQL** (database)
- **Pandas, NumPy, Matplotlib** (analysis + plots)

---

## 📊 Dashboard Previews  
- Sentiment distribution  
- Most common positive/negative phrases  
- Influencer action frequency  
- Engagement statistics per video  

---
