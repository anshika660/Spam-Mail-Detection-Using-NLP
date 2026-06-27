# Spam-Mail-Detection-Using-NLP
Machine Learning project for detecting spam emails using NLP, TF-IDF Vectorization and Logistic Regression with complete preprocessing and evaluation.

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-green?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</p>

---

# 📌 Project Overview

Spam emails and SMS messages are one of the most common cybersecurity problems today. This project builds a Machine Learning model capable of automatically classifying messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques.

The project demonstrates a complete machine learning workflow including data preprocessing, feature engineering, model training, evaluation, and prediction.

---

# 🎯 Objectives

- Detect spam messages automatically.
- Learn Natural Language Processing (NLP).
- Perform text preprocessing.
- Convert text into numerical vectors using TF-IDF.
- Train a Machine Learning model.
- Evaluate model performance using multiple metrics.

---

# 📂 Dataset

**Dataset:** SMS Spam Collection Dataset

The dataset contains SMS messages labelled as:

- Spam
- Ham (Non-Spam)

### Dataset Statistics

| Item | Value |
|------|-------|
| Total Messages | 5572 |
| Spam Messages | 747 |
| Ham Messages | 4825 |

Source:

https://archive.ics.uci.edu/ml/datasets/sms+spam+collection

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- NLTK
- TF-IDF Vectorizer
- Logistic Regression
- Jupyter Notebook

---

# ⚙️ Machine Learning Workflow

```
Dataset
     │
     ▼
Data Cleaning
     │
     ▼
Text Preprocessing
     │
     ▼
TF-IDF Vectorization
     │
     ▼
Train/Test Split
     │
     ▼
Logistic Regression
     │
     ▼
Prediction
     │
     ▼
Performance Evaluation
```

---

# 📋 Project Steps

### Step 1
Import required libraries.

### Step 2
Load the SMS Spam Collection Dataset.

### Step 3
Explore the dataset.

### Step 4
Remove unnecessary columns.

### Step 5
Check missing values and duplicate records.

### Step 6
Encode labels into numerical format.

### Step 7
Perform text preprocessing.

- Lowercase conversion
- Remove punctuation
- Tokenization
- Remove stopwords

### Step 8
Convert text into numerical features using TF-IDF.

### Step 9
Split the dataset into training and testing sets.

### Step 10
Train Logistic Regression model.

### Step 11
Predict test samples.

### Step 12
Evaluate the model using different performance metrics.

---

# 📊 Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# 📈 Visualizations

The project includes visualizations such as:

- Target Distribution
- Confusion Matrix
- Text Feature Analysis

---

# 📁 Repository Structure

```
Spam-Mail-Detection-Using-NLP
│
├── data
│   └── README.md
│
├── Spam_Mail_Detector.ipynb
│
├── requirements.txt
│
├── README.md
│
├── LICENSE
│
└── .gitignore
```

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/anshika660/Spam-Mail-Detection-Using-NLP.git
```

Go inside the project

```bash
cd Spam-Mail-Detection-Using-NLP
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook using Jupyter Notebook.

---

# 🚀 Future Improvements

- Deploy using Streamlit
- Add Word Cloud visualization
- Compare multiple ML algorithms
- Save trained model using Joblib
- Build REST API using Flask/FastAPI
- Deploy on Render or Hugging Face Spaces

---

# 💡 Learning Outcomes

Through this project, I gained practical experience in:

- Natural Language Processing (NLP)
- Text Preprocessing
- Feature Engineering
- TF-IDF Vectorization
- Logistic Regression
- Model Evaluation
- Machine Learning Pipeline Development

---

# 👩‍💻 Author

**Anshika Sharma**

Computer Science (AI & Data Science)

Passionate about Artificial Intelligence, Machine Learning, Data Science and NLP.

GitHub:
https://github.com/anshika660

---

## ⭐ If you found this project useful, consider giving it a star.
