# 📰 Fake News Detector

This is a Machine Learning project that aims to identify and classify fake news articles. The project uses Natural Language Processing (NLP) techniques combined with supervised learning models such as **Logistic Regression** and **Random Forest Classifier** to determine whether a news article is real or fake.

## 🔍 Features

- Preprocessing of news text (tokenization, stopword removal, vectorization)
- Model training with Logistic Regression and Random Forest
- Accuracy comparison of both models
- Prediction on custom news headlines

## 📁 Dataset

The dataset used is the **Fake and Real News Dataset**, which contains thousands of news headlines labeled as fake or real. It includes:
- Title of the article
- Text/content
- Label (FAKE/REAL)

## 🧠 Models Used

- **Logistic Regression** – A linear model for binary classification
- **Random Forest Classifier** – An ensemble learning method using decision trees

## 🛠️ Technologies

- Python
- Scikit-learn
- Pandas
- NumPy
- Jupyter Notebook / Google Colab

## 🚀 How to Run

1. Clone the repository:

2. Install dependencies:

3. Run the notebook or script:

## ✅ Results

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| 96%      |
| Random Forest      | 93%      |

Logistic Regression performed slightly better in this case, with higher precision and recall on the test set.

## 📷 Sample Prediction

```python
Enter News Title: "Government declares nationwide holiday"
Prediction: REAL
📌 Conclusion
This project demonstrates the effectiveness of classical ML algorithms in detecting fake news based on textual data. You can further enhance the model using advanced techniques like TF-IDF, LSTM, or BERT for deep learning-based classification.

📎 Author: Aman Meena
