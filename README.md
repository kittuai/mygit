# NLP Foundations Workshop: From Preprocessing to tf-idf  
**Course:** PROG8245 – Machine Learning Programming  
**Team:** Team 5 – Krishna (9050861), Mandeep Singh (8989367), Kumari Nikitha Singh (9053016)  
**Repository Name:** IRBasics-VectorSpaceProximity-workshop

---

## 🧠 Workshop Objective

This workshop demonstrates a full NLP pipeline for information retrieval using real-world text data.  
It covers all foundational vector space techniques, culminating in semantic search using TF-IDF and cosine similarity.

---

## 👥 Team Members

| Name                  | Student ID |
|-----------------------|------------|
| Krishna               | 9050861    |
| Mandeep Singh         | 8989367    |
| Kumari Nikitha Singh  | 9053016    |

---

## 📚 Dataset Description

- **Name:** 20 Newsgroups  
- **Source:** [scikit-learn fetch_20newsgroups](https://scikit-learn.org/stable/datasets/real_world.html#newsgroups-dataset)  
- **License:** Public  
- **Usage:** We used a subset of 20 documents for faster development and clarity.

---

## 💻 Environment Setup

This project uses Python 3 and common data science libraries. A `requirements.txt` file is provided for easy setup.

### 🔧 To install dependencies:

```bash
pip install -r requirements.txt
```

Or manually install core packages:

```bash
pip install scikit-learn pandas numpy nltk
```

### 🧾 `requirements.txt` contents:
```
scikit-learn==1.4.1
pandas==2.2.1
numpy==1.26.4
nltk==3.8.1
```

### 📝 NLTK Setup:
Inside the notebook, run this once to download stopwords:

```python
import nltk
nltk.download('stopwords')
```

---

## 📂 File Structure

```
IRBasics-VectorSpaceProximity-workshop/
│
├── IRBasics_VectorSpaceProximity.ipynb   # Main notebook (code + markdown + tests)
├── requirements.txt                      # Dependency list
└── README.md                             # This file
```

---

## 🔍 Concepts Implemented

1. Tokenization  
2. Normalization (Stopword removal + Stemming)  
3. Term-Document Incidence Matrix  
4. Term Frequency (TF)  
5. Log Frequency Weighting  
6. Document Frequency (DF)  
7. Inverse Document Frequency (IDF)  
8. TF-IDF Computation  
9. Phrase Query via Cosine Similarity  

---

## 📊 Key Outcomes

- Learned how to preprocess and vectorize real-world text data  
- Applied term-based and document-based frequency scoring  
- Built a full semantic retrieval system using cosine similarity  
- Practiced modular code development and team collaboration  

---

## ✅ Submission Checklist

- [x] Completed `.ipynb` notebook with 9 steps + phrase query
- [x] Team member names and IDs listed
- [x] Markdown explanations and labeled talking points
- [x] Phrase search logic using TF-IDF + cosine similarity
- [x] `README.md` with setup instructions and dataset info
- [x] `requirements.txt` with all used libraries
- [x] Public GitHub repo created
- [x] Git URL submitted to professor with subject line:  
  `PROG8245 - IR Basics & Vector Space Proximity Foundations Workshop, Team #5`

---

## 📘 License

The dataset is publicly available via Scikit-learn.  
Notebook and code are developed solely for academic use by Team 5, Conestoga College.

---

## 📞 Contact

For questions or academic feedback, reach out to any team member via internal Conestoga platforms.
