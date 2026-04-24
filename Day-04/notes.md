# Day 4 - Label Encoding (Categorical Data Processing)

## 📚 Topics Covered
- Categorical data
- Label Encoding
- Need for encoding in Machine Learning

## 🧠 Concepts Learned
- Machine Learning models cannot understand text (categorical data)
- Categorical data must be converted into numeric form
- Label Encoding assigns a unique number to each category
- It is suitable for ordinal data (data with order)

## 💻 What I Implemented
- Identified categorical columns in dataset
- Applied Label Encoding using sklearn
- Converted categorical values into numerical format

## ⚙️ Implementation Steps

### 1. Import LabelEncoder
```python
from sklearn.preprocessing import LabelEncoder

2. Create Encoder Object
le = LabelEncoder()
3. Apply Encoding
dataset['column_name'] = le.fit_transform(dataset['column_name'])
🔍 Example

Before Encoding:

Gender
Male
Female
Male

After Encoding:

Gender
1
0
1
⚠️ Limitations
Label Encoding introduces order between categories
Example:
Red = 0, Blue = 1, Green = 2
Model may assume:
Green > Blue > Red ❌ (which is not true)
💡 Key Takeaways
Label Encoding is simple and fast
Use it when data has order (ordinal data)
Avoid using it for nominal data (use One-Hot Encoding instead)
⚠️ Problems Faced
Confusion between Label Encoding and One-Hot Encoding
Understanding when to use each method
🔁 Revision Needed?
Yes (difference between encoding techniques)
