# 📝 NLP Project: Meesho Reviews Sentiment Analysis

This project focuses on analyzing customer reviews from Meesho, an Indian e-commerce platform, using Natural Language Processing (NLP). The goal is to extract meaningful insights such as sentiment, frequent topics, and opinions, and build machine learning models to classify customer sentiments.

## 👥 Team Members (Group 47)
- **Rohit Raju Kamble (2411AI61)**
- **Satyam Kumar (2411AI44)**
- **Abhisar Anand (2411AI43)**

---

## 📌 Objectives

1. **Data Collection**  
   Reviews were collected from Meesho product pages.

2. **Preprocessing**  
   - Text normalization  
   - Stopword removal  
   - Lemmatization  

3. **Sentiment Analysis**  
   - Labeled reviews as Positive, Negative, or Neutral.

4. **Aspect-Based Opinion Mining**  
   Identified opinions tied to specific aspects of products.

5. **Word Frequency and N-gram Analysis**  
   Explored unigrams, bigrams, and trigrams to discover frequently mentioned phrases.

6. **Visualization**  
   - Word clouds  
   - Bar plots of most frequent terms

7. **Classification Models**  
   Implemented and evaluated:
   - Naive Bayes
   - Logistic Regression
   - Random Forest
   - Support Vector Machine
   - BERT (Transformer-based model)

---

## 🧪 Results

The project compared several machine learning models using Bag of Words (BoW) and TF-IDF representations. Here are the classification performances:

| Model                   | Accuracy | Precision (avg) | Recall (avg) | F1-Score (avg) |
|------------------------|----------|------------------|--------------|----------------|
| Naive Bayes (BoW)      | 0.6956   | 0.70             | 0.70         | 0.69           |
| Naive Bayes (TF-IDF)   | 0.6976   | 0.70             | 0.70         | 0.69           |
| Random Forest (TF-IDF) | 0.6956   | 0.69             | 0.69         | 0.69           |
| XGBoost                | 0.6956   | 0.69             | 0.69         | 0.69           |
| SVM (TF-IDF)           | **0.7016** | **0.70**        | **0.70**     | **0.70**       |


📍 **Best Performing Model**:  
**SVM with TF-IDF**, achieving the highest accuracy and balanced precision/recall.


---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/meesho-review-nlp.git
   cd meesho-review-nlp
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook NLP_messho_review.ipynb
   ```

---


