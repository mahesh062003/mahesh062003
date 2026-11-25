## Mahesh Veeraiah R

MSc Advanced Computer Science at the University of Liverpool, with twelve months
as a software engineer and a background in Information Technology.

I work on **information retrieval and applied machine learning** — studying
which retrieval strategies actually work, building them into services, and
generalising them to new kinds of data. Two published papers.

Most of the repositories below report what a model does on held-out data,
including where it falls short. An accuracy figure without its caveats isn't a
result.

---

### Retrieval

**[ai-benchmark](https://github.com/mahesh062003/ai-benchmark)** — MSc
dissertation. Benchmarks BM25, dense (FAISS) and hybrid Reciprocal Rank Fusion
retrieval across six datasets in legal, medical and scientific domains, over
four language models with statistical significance testing. Where a dataset has
no retrieval ground truth it reports NULL rather than zero, so missing data
can't be mistaken for poor performance — enforced by a test suite.
`Python` `FAISS` `BM25` `pytest`

**[legal-rag-chatbot](https://github.com/mahesh062003/legal-rag-chatbot)** —
Retrieval-augmented chat over legal documents. Fuses dense and sparse retrieval
so paraphrased questions and exact section citations both resolve; a query
classifier routes conversational turns away from the index; responses stream
over websockets and cite their sources.
`Flask` `SocketIO` `LangChain` `FAISS`

**[sql-table-query](https://github.com/mahesh062003/sql-table-query)** —
Natural-language querying over relational tables. Each row is flattened into a
searchable document indexed for both semantic and keyword retrieval, with the
schema supplied through configuration rather than hardcoded.
`MySQL` `SQLAlchemy` `FAISS` `BM25`

### Applied machine learning

**[multimodal-stress-detection](https://github.com/mahesh062003/multimodal-stress-detection)**
— Stress inferred from facial expression, speech and wearable physiology, fused
by majority vote that still produces an assessment when a signal is missing.
CNN 87.6%, SVM 95.8%, XGBoost 92.75%. The Vision Transformer is kept as a
negative result — 97.8% train against 75.1% test — because the smaller CNN
generalised better. Published in IJIRT.
`TensorFlow` `PyTorch` `Whisper` `React`

**[lung-cancer-detection](https://github.com/mahesh062003/lung-cancer-detection)**
— Two CNNs behind one Flask application, reading CT slices and histopathology
slides. 96.2% on histology against 73.5% on CT; the gap is training data volume,
roughly 15,000 images to 800, rather than architecture.
`TensorFlow` `Flask`

**[alzheimer-mri-classifier](https://github.com/mahesh062003/alzheimer-mri-classifier)**
— Four-stage classification of cognitive decline from brain MRI, 94.15% test
accuracy. Documented as an upper bound: the split is image-level over a
pre-augmented dataset, so a patient-level split would score lower.
`TensorFlow` `scikit-learn`

---

Also here: a sign-language translation PWA
([gestura-fe](https://github.com/mahesh062003/gestura-fe) ·
[gestbackend](https://github.com/mahesh062003/gestbackend)), a terrain
classifier ([Terrain_classification-using-ML](https://github.com/mahesh062003/Terrain_classification-using-ML)),
a discharge-summary extraction pipeline
([post-discharge-tracking](https://github.com/mahesh062003/post-discharge-tracking)),
and a social platform for farmers
([cultivating-connection](https://github.com/mahesh062003/cultivating-connection)).

### Tools

`Python` `SQL` `JavaScript` · `TensorFlow` `Keras` `PyTorch` `scikit-learn`
`XGBoost` · `FAISS` `BM25` `sentence-transformers` `LangChain` ·
`Flask` `React` `Streamlit` · `MySQL` `SQLite` `MongoDB` · `Git` `pytest`

📍 Liverpool, United Kingdom · [LinkedIn](https://linkedin.com/in/maheshveeraiah)
