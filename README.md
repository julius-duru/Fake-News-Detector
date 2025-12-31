Production-ready Fake News Detection system built with NLP and Machine Learning.
The project demonstrates strong ML fundamentals, data leakage prevention, feature engineering, and model persistence.

# Fake News Detection (NLP + Machine Learning): https://news-detection-app.streamlit.app/

## Overview
This project implements a production-ready **Fake News Detection system** using Natural Language Processing and supervised machine learning. The model classifies news articles as **Fake (0)** or **Real (1)** using TF-IDF features and Logistic Regression.

The project emphasizes **correct ML methodology**, including data leakage prevention, proper label handling, and reproducible evaluation.

## Tech Stack
- Python
- Pandas & NumPy
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression
- Joblib

## Key ML Concepts Demonstrated
- Text preprocessing & normalization
- Feature engineering with TF-IDF
- Supervised classification
- Data leakage detection & correction
- Model evaluation (Precision, Recall, F1-Score)
- Model serialization for deployment

## Workflow
1. Load and merge fake and real news datasets
2. Clean and normalize textual data
3. Convert text to numerical features using TF-IDF
4. Train Logistic Regression classifier
5. Evaluate using classification metrics
6. Save trained model and vectorizer for inference

## Results
- Achieved strong classification performance with balanced precision and recall
- Ensured realistic evaluation by fixing target leakage issues

## Model Artifacts
- `vectorizer.jb`
- `lr_model.jb`

## Author
**Julius Duru**  
Presales Engineer | Data Science & Machine Learning

