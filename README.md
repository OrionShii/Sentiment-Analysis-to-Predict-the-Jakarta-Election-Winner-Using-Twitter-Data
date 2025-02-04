# 🗳️ Predicting the Jakarta Election Winner through Twitter Sentiment Analysis  

This project analyzes public sentiment on Jakarta election candidates using Twitter data to predict the winner. By leveraging **machine learning** and **natural language processing (NLP)**, the model processes tweets, classifies sentiments, and estimates candidate popularity.  

## 🚀 Features  
- **Twitter Data Crawling**: Automated tweet collection using Tweet Harvest.  
- **Sentiment Labeling**: Manual classification of tweets as positive or negative.  
- **Text Preprocessing**: Lemmatization, tokenization, stopword removal, and noise reduction.  
- **Feature Representation**: Transforming text into numerical vectors using TF-IDF.  
- **Machine Learning Models**:  
  - 🔹 Support Vector Machine (SVM)  
  - 🔹 Naïve Bayes  
- **Insight Extraction**: Identifying key words associated with sentiment trends.  
- **Prediction Analysis**: Estimating each candidate’s electability based on sentiment proportions.  

## 📊 Workflow  
1. **Data Collection**: Extract tweets related to Jakarta election candidates.  
2. **Data Cleaning & Preprocessing**: Normalize text for better model performance.  
3. **Sentiment Classification**: Train ML models to predict tweet sentiment.  
4. **Analysis & Prediction**: Compare sentiment trends to actual election results.  

## 🔧 Tech Stack  
- **Python** (Pandas, Scikit-learn, NLTK, Tweepy)  
- **Machine Learning** (SVM, Naïve Bayes)  
- **Natural Language Processing** (TF-IDF, Tokenization, Lemmatization)  

## 📌 Installation  
```bash
# Clone this repository
git clone https://github.com/yourusername/jakarta-election-sentiment.git

# Navigate to project folder
cd jakarta-election-sentiment

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # For MacOS/Linux
venv\Scripts\activate  # For Windows

# Install dependencies
pip install -r requirements.txt

```
📌 Results
Extracted top keywords associated with positive/negative sentiments.
Predicted each candidate's winning prospects based on sentiment analysis.
Compared sentiment predictions with actual election results.

## 👥 Contributors
- [@Vemas7731](https://github.com/Vemas7731)
- [@FauzanZamz](https://github.com/FauzanZamz)
- [@adamrobin](https://github.com/adamrobin)
- [@asrulfami](https://github.com/asrulfami)
