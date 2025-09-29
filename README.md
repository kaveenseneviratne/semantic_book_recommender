# 📚 Semantic Book Recommender  

## 📖 Overview  
⚡ ML-powered recommendation system  
⚡ Semantic search + emotional tone analysis  
⚡ Personalized book suggestions  

---

## 🌟 Features  
- 🔍 Semantic understanding  
- 🎭 Emotion-aware filtering  
- 📚 Category browsing  
- 🖼️ Visual dashboard  
- ⚡ Real-time recommendations  

---

## 🛠️ Project Components  

### 1. `data_exploration.ipynb`  
- Data cleaning  
- Missing values handling  
- Exploratory Data Analysis (EDA)  
- Dataset preparation  

### 2. `vector_search.ipynb`  
- Vector embeddings  
- Semantic similarity search  
- Recommendation quality evaluation  

### 3. `sentiment_analysis.ipynb`  
- Emotion classification via LLMs  
- Emotion scores:  
  - 😀 Joy  
  - 😢 Sadness  
  - 🤢 Disgust  
  - 😲 Surprise  
  - 😡 Anger  
  - 😱 Fear  
  - 😐 Neutral  
- Emotion-based filtering  

### 4. `dashboard.py`  
- Built with **Gradio**  
- Features:  
  - 🔍 Semantic search  
  - 📚 Genre filtering  
  - 🎭 Emotion tone filtering  
  - 🖼️ Book gallery view  
  - ⚡ Instant recommendations  

---

## 🚀 Getting Started  

### 🔧 Prerequisites  
- Python **3.8+**  
- OpenAI API key  
- Hugging Face API token  

xc 
```bash
git clone https://github.com/kaveenseneviratne/semantic_book_recommender.git
cd semantic_book_recommender
pip install -r requirements.txt
cp .env.example .env
# add API keys in .env
