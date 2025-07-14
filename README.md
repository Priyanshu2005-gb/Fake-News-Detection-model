# 📰 Fake News Detection using Machine Learning

This project is a machine learning-based system designed to detect whether a news article is **real** or **fake**, based only on its textual content. It uses Natural Language Processing (NLP) and a classification model to analyze news headlines and articles.

---

## ✅ Project Features

- Binary classification: **Real (1)** or **Fake (0)**
- Text cleaning and preprocessing using regex
- Feature extraction using **TF-IDF Vectorizer**
- Model built using **Multinomial Naive Bayes**
- Accuracy: **93% on both training and testing data**
- Tested with custom inputs for practical validation

---

## 📁 Dataset

The dataset used is from Kaggle:  
**Fake and Real News Dataset**  
[Click here to view on Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)


---

## 🔍 Libraries Used

- `pandas`  
- `numpy`  
- `re` (for regular expressions)  
- `scikit-learn` (Naive Bayes, TF-IDF, accuracy score)  
- `matplotlib` (optional, for visualization)

---

## ⚙️ Steps Followed

1. Data loading and merging  
2. Text cleaning (lowercase, remove punctuation/numbers/symbols)  
3. TF-IDF vectorization  
4. Model training with Multinomial Naive Bayes  
5. Evaluation using accuracy and confusion matrix  
6. Manual testing with sample news

---

## 📊 Model Accuracy

- **Training Accuracy:** 93%  
- **Testing Accuracy:** 93%  
- Consistent accuracy indicates good generalization performance.

## 📁 How to Run

1. Download the files from this repository  
2. Open `FakeNewsDetection.ipynb` in Jupyter Notebook  
3. Run each cell in order  
4. Try with your own headlines to see predictions

---

## 🔗 Project Link

**GitHub Repository:**  
[Click here to view the project](https://github.com/Priyanshu2005-gb/Fake-News-Detection-model)


---

## 📚 References

- [Kaggle Dataset – Fake and Real News](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)  
- [TF-IDF Explanation – MonkeyLearn](https://monkeylearn.com/blog/what-is-tf-idf/)  
- [Naive Bayes Overview – Medium](https://medium.com/swlh/naive-bayes-classifier-explained-9d2b4b2a3d00)  
- [Text Cleaning Techniques – Analytics Vidhya](https://www.analyticsvidhya.com/blog/2021/06/text-cleaning-in-nlp-with-python/)  
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
