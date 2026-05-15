# NLP Sequence Modeling Mini Project

## Project Overview
This project focuses on sentiment classification of customer support messages using Natural Language Processing (NLP) and sequence modeling techniques.

The dataset contains customer support text messages labeled as:
- Positive
- Neutral
- Negative

The project includes:
- Dataset analysis
- Text preprocessing
- Text vectorization
- Baseline machine learning model
- LSTM sequence model
- Attention and transformer reflection

---
## Dataset Source
Dataset: Customer Support Text Classification Dataset  
Source: https://https://drive.google.com/drive/folders/1akV6po4Nrgkc3yQrJkzA6cJlV-wBvUYs?usp=sharing
---

## Dataset
Dataset file:
`customer_support_text_classification.csv`

Main columns used:
- `customer_message` → Input text
- `sentiment_label` → Target label

---

## Tasks Completed

### Task 1: Dataset Understanding
Performed exploratory analysis including:
- Number of records
- Target classes
- Sample messages
- Average text length
- Class distribution

### Task 2: Text Preprocessing
Applied preprocessing steps:
- Lowercasing
- Removing special characters
- Tokenization
- Stopword removal
- Sequence padding

### Task 3: Text Vectorization
Used tokenizer-based vectorization to convert text into numerical sequences suitable for deep learning models.

### Task 4: Baseline Model
Built a baseline sentiment classification model using:
- TF-IDF Vectorization
- Logistic Regression

Evaluation metrics:
- Accuracy
- Classification Report
- Confusion Matrix

### Task 5: Sequence Model
Built an LSTM-based sequence model using:
- Embedding Layer
- LSTM Layer
- Dense Output Layers

Loss Function:
- Sparse Categorical Crossentropy

Evaluation Metric:
- Accuracy

### Task 6: Attention and Transformer Reflection
Included a short discussion about:
- RNN limitations
- LSTM memory handling
- Attention mechanism
- Importance of transformers in modern NLP

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- NLTK

---

