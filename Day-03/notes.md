# Day 3 - Data Preprocessing (Missing Values & Standardization)

## 📚 Topics Covered
- Handling missing values
  - Imputation
  - Dropping
- Data Standardization
- Importance of preprocessing in ML

## 🧠 Concepts Learned
- Real-world datasets often contain missing (null) values
- Missing values can negatively affect model performance
- Two main approaches to handle missing data:
  - **Imputation**: Filling missing values using statistical methods
    - Mean (numerical data)
    - Median (for skewed data)
    - Mode (categorical data)
  - **Dropping**: Removing rows or columns with missing values
- Dropping data can lead to loss of information if used excessively
- Standardization scales data such that:
  - Mean = 0
  - Standard Deviation = 1
- Feature scaling is important for algorithms like:
  - KNN
  - SVM
  - Gradient Descent-based models

## 💻 What I Implemented
- Loaded dataset using pandas
- Checked missing values using:
  - `dataset.isnull()`
  - `dataset.isnull().sum()`
- Handled missing values using:
  - Mean imputation
  - Mode imputation
  - Dropping columns with too many missing values
- Applied Standardization using `StandardScaler` from sklearn

## ⚙️ Implementation Steps

### 1. Checking Missing Values
```python
dataset.isnull().sum()

2. Handling Missing Values (Imputation)
dataset['column_name'].fillna(dataset['column_name'].mean(), inplace=True)
3. Dropping Columns
dataset.drop(['column_name'], axis=1, inplace=True)
4. Feature & Target Split
X = dataset.drop('target_column', axis=1)
y = dataset['target_column']
5. Standardization
from sklearn.preprocessing import StandardScaler

scaler = StandardScaler()
scaler.fit(X)
X_scaled = scaler.transform(X)

⚠️ Problems Faced
Errors while reading dataset (encoding and parsing issues)
Confusion between when to drop vs impute missing values
Understanding how StandardScaler works internally

💡 Key Takeaways
Data preprocessing is a critical step before model building
Always check for missing values before training a model
Imputation helps preserve data, while dropping reduces dataset size
Standardization ensures all features are on the same scale
Proper preprocessing improves model performance significantly

👉 Data preprocessing = cleaning and transforming raw data into usable form so a machine learning model can use it properly.
🔧 What preprocessing includes

Typical steps you’ve already done:

Handling missing values (isnull, fillna, drop)
Encoding categorical data (text → numbers)
Removing unnecessary columns
Splitting features & target
Scaling data

🧠 What is Data Standardization
👉 This is a part of preprocessing
🎯 Definition
👉 Standardization = scaling data so that:

Mean = 0
Standard deviation = 1


🔁 Revision Needed?
Yes (StandardScaler and missing value handling strategies)
