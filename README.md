## 📝 Text Summarization using NLP 

This project demonstrates a simple but effective **Extractive** text summarization technique using **spaCy**, stopword removal, word frequency calculation, and sentence scoring.
Given a long paragraph, the model identifies the most informative sentences and produces a concise summary.

---

## 🔍 How It Works

The summarizer follows these steps:

**1. Load text input**

  A long paragraph is provided manually inside the notebook.

**2. Text preprocessing**

  Tokenization

  Removing stopwords (like "the", "is")

  Ignoring punctuation

  Lowercasing words

**3. Word frequency calculation**

  Frequently occurring (non-stopword) words receive higher weights.

**4. Sentence scoring**

  Each sentence is given a score based on the sum of its important word frequencies.

**5. Selecting top sentences**

  The top 30% of the highest-scoring sentences are extracted and combined to create the summary.

  ---

 ## 📓 Notebook Included

The main implementation is inside:
```
notebooks/text_sum_NLP.ipynb
``` 

---

## 🚀 How to Run

1. Install the required libraries:
```
pip install -r requirements.txt
```


2. Run Jupyter Notebook:
```
jupyter notebook
```

3. Open the project notebook:
```
notebooks/text_sum_NLP.ipynb
```
---

## 📦 Requirements

This project uses the following Python libraries:
```
spacy
numpy
```
---

## 📁 Repository Structure
```
text-summarization/
│── notebooks/
│   └── text_sum_NLP.ipynb
│── README.md
└── requirements.txt
```

---

## 📬 Author

Medha Ramanathan

GitHub: Medha-tech

----