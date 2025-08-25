# 📰 Fake News Detection with XGBoost

This project classifies news articles as fake or real using NLP and XGBoost. The pipeline includes data cleaning, text preprocessing, TF-IDF feature extraction, model training, and evaluation.

The dataset contains news from different domains (Politics, News, Other). Preprocessing includes tokenization, lemmatization, stopword removal, and cleaning of URLs, punctuation, and numbers.

The XGBoost model achieves high performance with metrics like Accuracy, Precision, Recall, F1, and ROC-AUC. SHAP values and feature importances provide interpretability and highlight the most influential words in predictions.

Users can run the provided Jupyter notebook or load the trained model to classify new articles. Future improvements could include transformer-based models, n-gram features, and a web app deployment.
