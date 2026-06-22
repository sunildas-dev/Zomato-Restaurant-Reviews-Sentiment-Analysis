# 🍽️ Zomato Restaurant Reviews Sentiment Analysis

## 📖 Project Overview

This project performs **Sentiment Analysis** on Zomato restaurant reviews using **Machine Learning** and **Natural Language Processing (NLP)**. The model classifies customer reviews into **Positive**, **Neutral**, and **Negative** sentiments, helping restaurants understand customer feedback and improve their services.

---

## 🎯 Objective

* Analyze customer reviews from Zomato.
* Clean and preprocess textual data.
* Convert text into numerical features using **TF-IDF**.
* Reduce feature dimensions using **TruncatedSVD**.
* Train and evaluate Machine Learning models.
* Improve model performance through **Hyperparameter Tuning**.

---

## 📂 Dataset

The project uses two datasets:

* **Zomato Restaurant Reviews.csv**
* **Zomato Restaurant names and Metadata.csv**

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Natural Language Processing (NLP)
* Pickle (.pkl)

---

## 🔄 Project Workflow

1. Load Dataset
2. Data Exploration
3. Data Cleaning
4. Text Normalization
5. Feature Engineering
6. TF-IDF Vectorization
7. TruncatedSVD (Dimensionality Reduction)
8. Train-Test Split
9. Model Training
10. Hyperparameter Tuning (GridSearchCV)
11. Model Evaluation
12. Model Saving using Pickle

---

## 🤖 Machine Learning Models

* Random Forest Classifier
* Decision Tree Classifier

---

## 📊 Model Performance

### Random Forest

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 78.17% |
| Precision | 75.35% |
| Recall    | 78.17% |
| F1-Score  | 73.50% |

The Random Forest model achieved the best performance and was selected as the final model.

---

## 📁 Repository Structure

```
Zomato-Restaurant-Reviews-Sentiment-Analysis
│
├── Sample_ML_Submission_Template.ipynb
├── Zomato project.pptx
├── best_sentiment_model.pkl
├── tfidf_vectorizer.pkl
├── svd_transformer.pkl
├── Zomato Restaurant reviews.csv
├── Zomato Restaurant names and Metadata.csv
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run all notebook cells sequentially.
5. Use the saved `.pkl` files to make predictions on new reviews.

---

## 📌 Future Improvements

* Deploy the model as a web application using Flask or Streamlit.
* Improve accuracy using advanced NLP techniques.
* Experiment with Deep Learning models such as LSTM or BERT.
* Add real-time sentiment prediction.

---

## 👨‍💻 Author

**Sunil Das**

LinkedIn:  linkedin.com/in/sunildas-dev   

GitHub:  https://github.com/sunildas-dev
