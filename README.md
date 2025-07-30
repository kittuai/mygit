
# PROG8245 – Embedding, Clustering, and Vectorization Workshop

## 📁 Repository Overview

This repository contains our team's submission for the **PROG8245 NLP Workshop**, where we implemented a complete pipeline to process natural language data, build statistical and neural models, and visualize word relationships using real-world corpora.

> **GitHub Repository**: [https://github.com/nikitha2002-bot/EmbeddingClusteringVectorizationWorkshop](https://github.com/nikitha2002-bot/EmbeddingClusteringVectorizationWorkshop)

## 👥 Team Members

| Name            | Student ID |
|-----------------|------------|
| Krishna Reddy   | 905861     |
| Mandeep Singh   | 8989361    |
| Kumari Nikitha  | 9053016    |

## 🧠 Workshop Highlights

This notebook demonstrates the full NLP pipeline and advanced vectorization strategies using the Simple English Wikipedia corpus.

### 🔧 Implemented Components:

- Document normalization, tokenization, stopword removal, and lemmatization
- Unigram, Bigram, Trigram, and generalized N-gram language models
- Laplace smoothing to address sparsity in probabilistic models
- Word2Vec Skip-Gram model (trained on custom corpus)
- Pretrained GloVe embeddings (glove-wiki-gigaword-50)
- Latent Semantic Analysis (Truncated SVD) for 2D vector visualization
- Comparative analysis of Word2Vec vs GloVe in tabular format

## 📊 Dataset Description

- **Name**: Wikipedia (Simple English)
- **Source**: [HuggingFace Datasets – wikipedia (20220301.simple)](https://huggingface.co/datasets/wikipedia)
- **License**: CC BY-SA 3.0
- **Used For**: Building language models and word embeddings from scratch

## 📦 Repository Contents

| File                                | Description |
|-------------------------------------|-------------|
| `EmbeddingClusteringVectorizationWorkshop.ipynb` | Main notebook with full implementation and documentation |
| `requirements.txt`                  | Python dependencies to run the notebook environment |
| `README.md`                         | Overview of the project, structure, and team info |

## 🚀 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/nikitha2002-bot/EmbeddingClusteringVectorizationWorkshop.git
   cd EmbeddingClusteringVectorizationWorkshop
   ```

2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch the notebook:
   ```bash
   jupyter notebook EmbeddingClusteringVectorizationWorkshop.ipynb
   ```

## 💬 Talking Points

Our notebook includes labeled **talking points** at key stages to explain design decisions, modeling trade-offs, and reflections that guided our approach — a key element of this peer-reviewed workshop.

## 🌟 Creative Distinction

To elevate our submission, we implemented:
- A generalized N-gram model (configurable to any order)
- Laplace smoothing with vocabulary-aware fallback
- Dual embedding strategies with visual projection for comparison
- Professionally formatted Markdown and interpretation blocks throughout
- Custom examples tested with real semantic queries (e.g., `"king is powerful"`)

## 📬 Submission Note

- Team GitHub URL: [https://github.com/nikitha2002-bot/EmbeddingClusteringVectorizationWorkshop](https://github.com/nikitha2002-bot/EmbeddingClusteringVectorizationWorkshop)
- Email subject: **PROG8245 - Embeddings, Clustering, and Vectorization Workshop, Team #___**

---

> © Conestoga College | PROG8245 | NLP Workshop | Summer 2025
