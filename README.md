# News Classifier: Fake News Detection with XGBoost

This project focuses on classifying news articles as real or fake using Natural Language Processing (NLP) and the XGBoost machine learning algorithm. The pipeline includes data cleaning, text preprocessing, TF-IDF feature extraction, model training, and evaluation. The dataset comprises news articles from various domains, including Politics, News, and Other categories.([GitHub][1], [GitHub][2])

---

## 📁 Project Structure

The repository is organized as follows:

```

.
├── Fake.csv                 # Dataset containing fake news articles
├── True.csv                 # Dataset containing real news articles
├── Technical_Task.html      # HTML report of the technical task
├── Technical_Task.ipynb     # Jupyter notebook for the technical task
├── .gitignore               # Git ignore rules
└── README.md                # Project documentation
```



---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

* [Python 3.6+](https://www.python.org/)
* [pip](https://pip.pypa.io/en/stable/)

### Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/manikrishna-m/news_classifier.git
   cd news_classifier
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**

   ```bash
   jupyter notebook Technical_Task.ipynb
   ```

   This notebook contains the full pipeline, including data loading, preprocessing, model training, evaluation, and interpretability analysis.

---

## 🧪 Model Overview

The project utilizes the XGBoost classifier, a gradient boosting algorithm known for its high performance and efficiency. The pipeline includes:

* **Data Cleaning**: Removing irrelevant information such as URLs, punctuation, and numbers.
* **Text Preprocessing**: Tokenization, lemmatization, and stopword removal.
* **Feature Extraction**: TF-IDF vectorization to convert text data into numerical features.
* **Model Training**: Training the XGBoost model on the processed data.
* **Evaluation**: Assessing model performance using metrics like Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
* **Interpretability**: Using SHAP values to understand model predictions and identify influential features.([Nature][3])

---

## 📊 Evaluation Metrics

The model's performance is evaluated using the following metrics:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **ROC-AUC**([GitHub][2], [MDPI][4])

These metrics provide a comprehensive understanding of the model's ability to correctly classify news articles as real or fake.([GitHub][1])

---

## 📄 License

This project is licensed under the MIT License.

---

For more detailed information and to explore the project's components, please visit the [news\_classifier repository](https://github.com/manikrishna-m/news_classifier).

---
