This project performs Sentiment Analysis on Lazada Product Reviews, aiming to classify customer reviews as positive, negative, or neutral. The project leverages TF-IDF (Term Frequency-Inverse Document Frequency) for feature extraction and applies various Machine Learning models for classification.

## Key Challenges Addressed

✅ Handling Out-of-Vocabulary (OOV) words in Lazada reviews.

✅ Processing Malaysia’s rojak language (a mix of Malay, English, and Chinese).

✅ Implementing efficient text preprocessing to improve classification accuracy.

✅ Conducting test cases to evaluate sentiment classification models.


## 4.1 Text Preprocessing

✔ Lowercasing – Converts text to lowercase.

✔ Removing Numbers & Punctuation – Cleans up unnecessary symbols.

✔ Handling Abbreviations – Expands common abbreviations.

✔ Stopword Removal – Eliminates irrelevant words to improve feature extraction.

✔ Handling Multilingual Text (Rojak Language) – Detects and processes Malay, English, and Chinese.

## 4.2 Feature Extraction (TF-IDF)

TF-IDF Vectorization:

Converts text into numerical feature vectors.

Weights terms based on importance within the dataset.


## 4.3 Model Training & Evaluation

We implemented three different Machine Learning models for classification:

### 1️⃣ Logistic Regression

Suitable for binary and multi-class classification.

Good baseline model for sentiment classification.

### 2️⃣ Support Vector Machine (SVM)

Effective for high-dimensional text data.

Finds the optimal hyperplane for classification.

### 3️⃣ Multinomial Naïve Bayes (MNB)

Works well with text data and word frequency-based features.

Assumes conditional independence of words, making it computationally efficient.

## 4.4 Evaluation Metrics

📊 Accuracy, Precision, Recall, F1-Score

📊 Confusion Matrix for sentiment classification

📊 Cross-validation to ensure robustness
