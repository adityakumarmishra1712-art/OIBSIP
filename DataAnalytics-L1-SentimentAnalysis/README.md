# Level 1 - Task 4: Sentiment Analysis

## 🎯 Project Objective
Build a machine learning pipeline that classifies text data into positive, negative, or neutral sentiment, providing actionable insights into public opinion and customer feedback.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Environment:** Jupyter Notebook
- **NLP / ML Libraries:** NLTK, Scikit-learn (TF-IDF, Naive Bayes, Logistic Regression / SVM)
- **Data & Visualisation:** Pandas, NumPy, Matplotlib, Seaborn, WordCloud

---

## 📋 Key Steps & Workflow
1. **Data Exploration & Class Distribution:**
   - Inspected dataset structure and analyzed sentiment balance across positive, negative, and neutral classes.
2. **Text Preprocessing Pipeline:**
   - Case normalization (lowercasing), punctuation removal, tokenization, stopword filtering, and lemmatization/stemming.
3. **Feature Extraction:**
   - Vectorized cleaned text data using **TF-IDF Vectorizer**.
4. **Model Training & Evaluation:**
   - Train/Test Split (80/20).
   - Trained classification models (e.g., Multinomial Naive Bayes & Logistic Regression).
   - Evaluated performance using Accuracy, Precision, Recall, F1-score, and Confusion Matrix.
5. **Visualisation & Insights:**
   - Generated sentiment frequency bar plots and **WordClouds** for key sentiment categories.
   - Performed error analysis on misclassified records.
