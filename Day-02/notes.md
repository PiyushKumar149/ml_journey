# Day 2 - Dataset Collection & Importing Data

## 📚 Topics Covered
- Different sources of datasets
- Importing datasets from Kaggle
- UCI Machine Learning Repository
- Google Dataset Search
- Kaggle API setup and usage

## 🧠 Concepts Learned
- Machine Learning requires good quality datasets
- Datasets can be obtained from multiple sources
- Kaggle API allows direct downloading of datasets into the working environment
- Proper dataset handling is the first step before preprocessing

## 💻 What I Implemented
- Explored datasets from:
  - Kaggle
  - UCI Machine Learning Repository
  - Google Dataset Search
- Set up Kaggle API
- Downloaded dataset using Kaggle API in notebook
- Loaded dataset into pandas DataFrame

## ⚙️ Steps to Set Up Kaggle API (Google Colab)

1. Go to Kaggle account settings  
2. Click on **Create New API Token**  
3. Make a kaggle.json file in notepad having details like : 
{
  username: "",
  key : ""
  }

4. Upload `kaggle.json` in Colab:
```python

Create Kaggle folder:
!mkdir -p ~/.kaggle

Move the file:
!cp kaggle.json ~/.kaggle/

Set permissions:
!chmod 600 ~/.kaggle/kaggle.json

Download dataset:
!kaggle datasets download -d dataset-name

Unzip dataset:
!unzip dataset-name.zip

⚠️ Problems Faced
Difficulty in setting up Kaggle API initially
Understanding where to place kaggle.json file
Command errors while downloading dataset
💡 Key Takeaways
Knowing how to get datasets is a fundamental ML skill
Kaggle API automates dataset downloading
Correct setup is necessary for smooth workflow
🔁 Revision Needed?
Yes (Kaggle API commands and setup steps)
