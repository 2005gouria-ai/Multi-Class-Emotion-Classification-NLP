# Multi-Class Emotion Classification using NLP

## Project Overview

This project focuses on building a Machine Learning-based Natural Language Processing (NLP) system to classify human emotions from textual data.

It uses text preprocessing, feature extraction techniques, and supervised machine learning algorithms to identify emotions from input text.

## Technical Stack

- Python
- Pandas
- NumPy
- NLTK
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

### 1. Data Ingestion and Preparation
- Load the emotion classification dataset.
- Explore dataset structure and features.
- Handle missing and duplicate values.
- Map emotion categories into numerical labels.

### 2. Text Preprocessing
- Convert text into lowercase.
- Remove punctuation and numerical characters.
- Eliminate stopwords using NLTK.
- Apply custom text filtering.

### 3. Feature Engineering
Compare two text vectorization techniques:

- Bag-of-Words (BoW)
- TF-IDF with Unigrams and Bigrams.

### 4. Model Training

Implement and compare:

- Logistic Regression
- Multinomial Naive Bayes

Both models are trained for multi-class emotion prediction.

### 5. Model Evaluation

Evaluate model performance using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

Visualize model performance using Matplotlib and Seaborn.

## Project Structure

```text
Multi-Class-Emotion-Classification-NLP/
│
├── dataset/
│   └── emotion_dataset.csv
│
├── notebooks/
│   └── emotion_classification.ipynb
│
├── README.md
│
└── requirements.txt
```

## Installation and Setup

### 1. Clone Repository

```bash
git clone https://github.com/your-username/Multi-Class-Emotion-Classification-NLP.git
```

### 2. Navigate to Project

```bash
cd Multi-Class-Emotion-Classification-NLP
```

### 3. Install Dependencies

```bash
pip install pandas numpy nltk scikit-learn matplotlib seaborn jupyter
```

### 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook inside the `notebooks` folder.

## Expected Output

The trained model predicts the emotion category associated with the given text.

Model performance is compared using classification metrics and confusion matrix visualizations.

## Applications

- Sentiment and emotion analysis
- Social media text analysis
- Customer feedback analysis
- Chatbot development
- Human-computer interaction

## Future Improvements

- Implement deep learning models such as LSTM and BiLSTM.
- Experiment with Transformer-based models such as BERT.
- Develop a real-time emotion prediction web application using Streamlit.
- Improve classification performance through hyperparameter tuning.

## Author

Sunny Singh

**Interests:** Data Science | Machine Learning | Natural Language Processing | Artificial Intelligence
