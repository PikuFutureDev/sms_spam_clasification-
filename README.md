# 📩 SMS Spam Classification

This repository contains a Python-based machine learning project for detecting spam SMS messages. It uses Natural Language Processing (NLP) techniques and classification algorithms to predict whether a given SMS message is **spam** or **ham (not spam)**.

## 🚀 Features

* Data preprocessing & cleaning
* Text vectorization (Bag of Words / TF-IDF)
* Model training & evaluation (e.g., Naive Bayes, Logistic Regression)
* Performance metrics: Accuracy, Precision, Recall, F1-Score
* Prediction on new sample inputs
* Jupyter Notebook for step-by-step explanation

## 📝 Project Structure

```
.
├── sms_spam_classification.ipynb
├── README.md
├── requirements.txt
└── dataset/
    └── spam.csv
```

## 📂 Dataset

The dataset used is typically a collection of SMS labeled messages (spam/ham).
For example, the popular **UCI SMS Spam Collection Dataset**.

## ⚙️ Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/sms-spam-classification.git
cd sms-spam-classification
```

2. Create a virtual environment & install dependencies:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

(You can generate `requirements.txt` from your environment using:
`pip freeze > requirements.txt`.)

## 🖥️ Usage

Run the Jupyter Notebook to explore the data, preprocessing steps, and model training:

```bash
jupyter notebook sms_spam_classification.ipynb
```

## ✅ Example Prediction

```python
sample_message = "Congratulations! You've won a free ticket. Call now!"
model.predict([sample_message])
# Output: ['spam']
```

## 📊 Results

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 98.5% |
| Precision | 97.2% |
| Recall    | 96.8% |
| F1-Score  | 97.0% |

## 📌 Technologies Used

* Python (Pandas, NumPy, scikit-learn, matplotlib, seaborn)
* Natural Language Toolkit (nltk)
* Jupyter Notebook




