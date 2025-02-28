
# Topic Modeling on 20 Newsgroups Dataset

This repository contains an implementation of various topic modeling techniques on the 20 Newsgroups dataset. The dataset is preprocessed using TF-IDF and CountVectorizer, followed by topic modeling using:



- Latent Dirichlet Allocation (LDA) (Scikit-learn & Gensim)
- Non-negative Matrix Factorization (NMF)
- Hierarchical Dirichlet Process (HDP)
- Guided LDA (attempted but not effective)


## Features:

✅ Preprocessing using TfidfVectorizer and CountVectorizer

✅ Topic modeling using LDA, NMF, and HDP

✅ Coherence Score Calculation for LDA evaluation

✅ pyLDAvis visualization for topic distribution

✅ Comparison between Scikit-learn & Gensim LDA


## Requirements

Install the required dependencies using:

```python
pip install gensim pyLDAvis guidedlda bertopic top2vec

```


## Usage

Run the script to:

1. Train different topic models.
2. Extract and display topics with top keywords.
3. Visualize the learned topics using pyLDAvis.

This project can easily be usedd in document Classification with little changes 🚀






