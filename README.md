# Machine Learning for NLP  
**Ideological Classification of French Political Manifestos: A Comparative Study of NLP Representations and Linguistic Patterns**

---

## Project Overview  

This project was developed for the course *Machine Learning for Natural Language Processing*.

The objective is to analyze the Archelec corpus, a collection of French electoral documents, using a combination of:

- statistical text analysis  
- vector-space representations  
- unsupervised learning (topic modeling, clustering)  
- supervised learning (classification)  

The goal is to uncover latent political structures and evaluate whether textual features can predict political affiliation.

In addition to structured metadata, the project also includes an extension based on **raw manifesto texts**, focusing on the **1988 French legislative elections**. This extension explores whether political orientation can be directly inferred from textual content.

---

## Notebooks  

### 01 — Data Exploration & Preprocessing  
Dataset inspection, cleaning, text construction, and descriptive statistics.

### 02 — Vectorization & Statistical NLP  
Bag-of-Words, TF-IDF, document similarity, dimensionality reduction, and clustering.

### 03 — Topic Modeling (LDA)  
Identification of latent political topics and analysis of their distribution over time and across political groups.

### 04 — Supervised Classification  
Prediction of political support using Logistic Regression and SVM.

### 05 — Extension: Manifesto Text Classification  
Binary classification of political orientation (**Left vs Right**) using raw manifesto texts from the **1988 legislative elections**.  
This notebook includes:
- text preprocessing and cleaning  
- TF-IDF vectorization  
- Logistic Regression classification  
- performance evaluation (classification report, confusion matrix)  
- interpretation through most informative words  

This extension highlights the challenges and advantages of working with unstructured political text compared to structured metadata.

---

## Methods Used  

- Text preprocessing (tokenization, cleaning, stopword removal)  
- Bag-of-Words and TF-IDF  
- Cosine similarity  
- Dimensionality reduction (SVD)  
- K-Means clustering  
- Latent Dirichlet Allocation (LDA)  
- Logistic Regression  
- Support Vector Machines (SVM)  

---

## How to Use  

1. Open the notebooks in Google Colab or Jupyter.  
2. Upload the required dataset when prompted.  
3. Run cells sequentially.  




