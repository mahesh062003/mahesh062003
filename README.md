<h1 align="center">Mahesh Veeraiah R</h1>

<p align="center">
  MSc Advanced Computer Science · University of Liverpool<br>
  AI, RAG &amp; applied machine learning
</p>

<p align="center">
  <a href="https://linkedin.com/in/maheshveeraiah">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:maheshveeraiah4@gmail.com">
    <img src="https://img.shields.io/badge/Email-333333?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
  <img src="https://img.shields.io/badge/Liverpool,_UK-555555?style=flat-square&logo=googlemaps&logoColor=white" alt="Liverpool, UK">
</p>

---

## About

I work on **AI and machine learning, particularly RAG and retrieval** —
studying which retrieval strategies actually work, building them into services,
and generalising them to new kinds of data.

That thread runs through most of what's here. One project benchmarks retrieval
strategies formally, another builds them into a document assistant, a third
applies them to relational data. Alongside that sits a line of medical-imaging
work and two published papers.

Most repositories below report what a model does on held-out data, including
where it falls short. An accuracy figure without its caveats isn't a result.

**Currently** looking for roles in applied ML, retrieval or software
engineering.

---

## Experience & Education

| | |
|---|---|
| **Software Engineer Intern** · Mary Martin Software Solutions | Jan – Dec 2025 |
| **MSc Advanced Computer Science** · University of Liverpool | 2026 – 2027 |
| **B.Tech Information Technology** · Sri Ramakrishna Engineering College | 2021 – 2025 |

---

## Selected work

### Retrieval

**[ai-benchmark](https://github.com/mahesh062003/ai-benchmark)** — *MSc dissertation*
Benchmarks BM25, dense (FAISS) and hybrid Reciprocal Rank Fusion retrieval
across six datasets in legal, medical and scientific domains, over four
language models with statistical significance testing. Where a dataset has no
retrieval ground truth it reports NULL rather than zero, so missing data can't
be mistaken for poor performance — enforced by a test suite.
<br>`Python` `FAISS` `BM25` `pytest`

**[legal-rag-chatbot](https://github.com/mahesh062003/legal-rag-chatbot)**
Retrieval-augmented chat over legal documents. Fuses dense and sparse retrieval
so paraphrased questions and exact section citations both resolve; a query
classifier routes conversational turns away from the index; responses stream
over websockets and cite their sources.
<br>`Flask` `SocketIO` `LangChain` `FAISS`

**[sql-table-query](https://github.com/mahesh062003/sql-table-query)**
Natural-language querying over relational tables. Each row is flattened into a
searchable document indexed for both semantic and keyword retrieval, with the
schema supplied through configuration rather than hardcoded.
<br>`MySQL` `SQLAlchemy` `FAISS` `BM25`

### Applied machine learning

**[multimodal-stress-detection](https://github.com/mahesh062003/multimodal-stress-detection)** — *published*
Stress inferred from facial expression, speech and wearable physiology, fused by
majority vote that still produces an assessment when a signal is missing. CNN
87.6%, SVM 95.8%, XGBoost 92.75%. The Vision Transformer is kept as a negative
result — 97.8% train against 75.1% test — because the smaller CNN generalised
better.
<br>`TensorFlow` `PyTorch` `Whisper` `React`

**[lung-cancer-detection](https://github.com/mahesh062003/lung-cancer-detection)**
Two CNNs behind one Flask application, reading CT slices and histopathology
slides. 96.2% on histology against 73.5% on CT; the gap is training data volume,
roughly 15,000 images to 800, rather than architecture.
<br>`TensorFlow` `Flask`

**[alzheimer-mri-classifier](https://github.com/mahesh062003/alzheimer-mri-classifier)**
Four-stage classification of cognitive decline from brain MRI, 94.15% test
accuracy. Documented as an upper bound: the split is image-level over a
pre-augmented dataset, so a patient-level split would score lower.
<br>`TensorFlow` `scikit-learn`

### Also here

[**gestura-fe**](https://github.com/mahesh062003/gestura-fe) ·
[**gestbackend**](https://github.com/mahesh062003/gestbackend) — sign-language
translation PWA rendering speech and text as word-level sign animations, with a
JWT auth service
<br>[**Terrain_classification-using-ML**](https://github.com/mahesh062003/Terrain_classification-using-ML)
— four-class terrain classifier, 90.4% on a held-out test set
<br>[**post-discharge-tracking**](https://github.com/mahesh062003/post-discharge-tracking)
— extraction pipeline pulling thirteen fields from PDF discharge summaries
<br>[**cultivating-connection**](https://github.com/mahesh062003/cultivating-connection)
— social platform for farmers, built with Streamlit over SQLite

---

## Publications

**Facial and Speech Emotion Detection for Stress Monitoring**
*International Journal of Innovative Research in Technology*, vol. 11, no. 12,
pp. 756–759, May 2025 · [read](https://ijirt.org/article?manuscript=177475)

**AI-based Multimodal Stress Detection and Physiological Tracking Application**
*ACT 2026 — International Conference on Advances in Computing, Control and
Telecommunication Technologies*

---

## Tools

**Languages** `Python` `SQL` `JavaScript` `C`

**Machine learning** `TensorFlow` `Keras` `PyTorch` `scikit-learn` `XGBoost` `OpenCV`

**Retrieval & NLP** `FAISS` `BM25` `sentence-transformers` `LangChain` `NLTK` `spaCy` `Whisper`

**Web & data** `Flask` `React` `Streamlit` `MySQL` `SQLite` `MongoDB` `SQLAlchemy`

**Tooling** `Git` `pytest`
