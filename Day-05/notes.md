# Day 5 - Imbalanced Data & Text Feature Extraction (TF-IDF)
📅 Date: 27 April 2026

## 📚 Topics Covered
- Handling Imbalanced Datasets
- Feature Extraction of Text Data (TF-IDF)
- Numerical Data Preprocessing (Use Case)
- Text Data Preprocessing (Use Case)

## 🧠 Concepts Learned

### 🔹 Imbalanced Dataset
- Occurs when one class has significantly more samples than another
- Example: Fraud detection (few fraud cases, many normal cases)
- Can lead to biased models

### 🔹 Handling Imbalance
- Undersampling (reduce majority class)
- Oversampling (increase minority class)
- Sampling using `.sample()` function

---

### 🔹 TF-IDF Vectorizer
- Converts text data into numerical form
- Based on importance of words in a document

- TF (Term Frequency): how often a word appears  
- IDF (Inverse Document Frequency): how rare the word is  

- Important words get higher values

---

### 🔹 Numerical Data Preprocessing
- Handling missing values  
- Standardization using StandardScaler  
- Feature scaling improves model performance  

---

### 🔹 Text Data Preprocessing
Steps:
- Remove special characters (regex)
- Convert to lowercase
- Tokenization (split words)
- Remove stopwords
- Apply stemming

---

## 💻 What I Implemented
- Handled imbalanced dataset using sampling
- Applied TF-IDF vectorization on text data
- Built text preprocessing pipeline using:
  - regex
  - stopwords
  - PorterStemmer
- Worked on both numerical and text preprocessing use cases

---

## ⚙️ Implementation Steps

### 1. Handling Imbalance
```python
legit_sample = legit.sample(n=492)

2. TF-IDF Vectorization
from sklearn.feature_extraction.text import TfidfVectorizer

vectorizer = TfidfVectorizer()
X = vectorizer.fit_transform(X)
3. Text Preprocessing Function
def Stemming(content):
    content = re.sub("[^a-zA-Z]", " ", content)
    content = content.lower()
    content = content.split()
    content = [port_stem.stem(word) for word in content if word not in stopwords.words("english")]
    return " ".join(content)
⚠️ Problems Faced
Understanding TF-IDF working
Confusion in handling imbalanced datasets
Debugging text preprocessing errors
💡 Key Takeaways
Imbalanced data can mislead models
TF-IDF is essential for NLP tasks
Text preprocessing is critical before feature extraction
Proper preprocessing improves model performance
🔁 Revision Needed?
Yes (TF-IDF intuition and imbalance techniques)



