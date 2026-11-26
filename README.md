<h1 align="center">Mahesh Veeraiah R</h1>

<p align="center">
  MSc Advanced Computer Science · University of Liverpool<br>
  AI · Applied machine learning · Software engineering
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

MSc Advanced Computer Science student at the University of Liverpool, with a
B.Tech in Information Technology and twelve months of industry experience as a
software engineer intern.

I build machine learning systems end to end — training and comparing models,
then serving them behind an API or interface. Recent work spans convolutional
networks for image classification, transformer and classical models for text,
question answering over document collections, and natural-language interfaces
to databases. Alongside that, two published papers and an MSc dissertation on
how to evaluate these systems properly.

Every repository here reports measured results on held-out data, including
where performance falls short.

**Interests** — applied machine learning · natural language processing ·
computer vision · large language models · backend and software engineering

**Currently** open to graduate roles in AI, machine learning and software
engineering.

---

## Experience & Education

| | |
|---|---|
| **Software Engineer Intern** · Mary Martin Software Services | Jan – Dec 2025 |
| **MSc Advanced Computer Science** · University of Liverpool | 2026 – 2027 |
| **B.Tech Information Technology** · Sri Ramakrishna Engineering College | 2021 – 2025 |

---

## Selected work

**[ai-benchmark](https://github.com/mahesh062003/ai-benchmark)** — *MSc dissertation*
Compares three search strategies across six datasets in legal, medical and
scientific domains, over four language models with statistical significance
testing. Where a dataset has no ground truth it reports NULL rather than zero,
so missing data can't be mistaken for poor performance — enforced by a test
suite.
<br>`Python` `FAISS` `BM25` `pytest`

**[multimodal-stress-detection](https://github.com/mahesh062003/multimodal-stress-detection)** — *published*
Stress inferred from facial expression, speech and wearable physiology, fused by
majority vote that still produces an assessment when a signal is missing. CNN
87.6%, SVM 95.8%, XGBoost 92.75%. The Vision Transformer is kept as a negative
result — 97.8% train against 75.1% test — because the smaller CNN generalised
better.
<br>`TensorFlow` `PyTorch` `Whisper` `React`

**[legal-rag-chatbot](https://github.com/mahesh062003/legal-rag-chatbot)**
Question answering over legal documents. Combines semantic and keyword search so
both loosely worded questions and exact section references resolve; a classifier
routes conversational turns away from the index; answers stream over websockets
and cite their sources.
<br>`Flask` `SocketIO` `LangChain` `FAISS`

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

**[sql-table-query](https://github.com/mahesh062003/sql-table-query)**
Natural-language querying over relational tables. Each row becomes a searchable
document indexed for both semantic and keyword matching, with the schema
supplied through configuration rather than hardcoded.
<br>`MySQL` `SQLAlchemy` `FAISS` `BM25`

## Other projects

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

**NLP** `RAG` `FAISS` `BM25` `sentence-transformers` `LangChain` `NLTK` `spaCy` `Whisper`

**Web & data** `Flask` `React` `Streamlit` `MySQL` `SQLite` `MongoDB` `SQLAlchemy`

**Tooling** `Git` `pytest`
