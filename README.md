# FAKE_NEWS_DETECTION
##  Overview
This project focuses on detecting **fake news articles** using machine learning.  
The goal is to classify news articles as **Real** or **Fake** by preprocessing the text and applying different machine learning classifiers.

##  Dataset
- **Source:** [Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)  
- Contains two categories of news articles: **Fake** and **Real**.  
- Includes thousands of labeled news headlines and content.

##  Methodology
1. **Data Preprocessing**
   - Removal of punctuation, numbers, and special characters.
   - Tokenization of text.
   - Removal of stopwords.
   - Lemmatization/Stemming to reduce words to their root form.

2. **Feature Extraction**
   - TF-IDF Vectorization for representing text numerically.

3. **Model Training**
   - Logistic Regression  
   - Naïve Bayes  
   - Random Forest  

4. **Model Evaluation**
   - Accuracy  
   - Precision  
   - F1-Score  

##  Results
- The models were compared based on classification metrics.
- Logistic Regression and Naïve Bayes performed well with high accuracy.
- Random Forest captured complex relationships but required more computation.

## Tech Stack
- **Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, nltk  

## Future Improvements
- Use advanced deep learning models (LSTM, BERT).  
- Implement real-time fake news detection API.  
- Improve preprocessing with named entity recognition (NER).  

---

### 🔗 Author
Developed as part of a **Machine Learning project** to explore text classification techniques.
