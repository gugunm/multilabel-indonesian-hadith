# FINAL TASK
[![jurnal](https://img.shields.io/badge/Jurnal-Telkom-blue.svg)](https://drive.google.com/open?id=12hS-1cEbCyjySE-0thvzRURnag44uBVU)
[![dataset](https://img.shields.io/badge/Dataset-Hadits-brightgreen.svg)](https://drive.google.com/open?id=1hInke1UE0z1Ih2b_qnDNPWJBEl1_ovu8)
[![poster](https://img.shields.io/badge/Poster-Laporan-red.svg)](https://drive.google.com/open?id=1HTmI08MmC2037v297vLdIJDJz43jij36)
[![Referensi](https://img.shields.io/badge/Referensi-Laporan-yellow.svg)](https://drive.google.com/open?id=1Y24MeAKQ5wT0qudgOYlefGYZYWFhRu7l)
[![Present](https://img.shields.io/badge/Materi-Presentasi-orange.svg)](https://drive.google.com/open?id=1LZrBeiBmLzfQWxLPDo8p2WkHRnysc2B5PY3D4HJgFXg)

# Step Untuk Menjalankan Program

#### 1. Program utama untuk running file yaitu **_Main.py**
#### 2. Sebelum running file **_Main.py** :
- Download model Word2vec dan model PoSTag pada link berikut.
  - [Model Word2vec - CBOW](https://drive.google.com/open?id=194Nv9GY8MTcHTi18w7vu7gXXZ21vFeTY) -- lalu simpan di folder input/cbow
  - [Model Word2vec - SkipGram](https://drive.google.com/open?id=1dFED-1wuUrqXUIQH1pb4f1EfDqXaok26) -- lalu simpan di folder input/skipgram
  - [Model PosTag](https://drive.google.com/open?id=1SNDp4tLR3CYl5HX7hTbjlVs_j6fC1R9M) -- lalu simpan di folder input/tagger
#### 3. Modules yang dibutuhkan pada project ini yaitu : 
- [NLTK](https://pypi.org/project/nltk/) -> ('nltk.download('punkt')')
- [GENSIM](https://pypi.org/project/gensim/) (Untuk Word2vec)
- [FASTTEXT](https://fasttext.cc/) (Untuk Fasttext)
- [NUMPY](https://pypi.org/project/numpy/) (Library matematika)
- [PANDAS](https://pypi.org/project/pandas/) (Manipulasi data csv)
- [SCIKIT-LEARN](https://pypi.org/project/scikit-learn/) (Klasifikasi menggunakan SVM)
- [SASTRAWI](https://pypi.org/project/Sastrawi/) (Remove Stopword dan Stemmer dalam Bahasa Indonesia)
- [CRF-TAGGER](https://pypi.org/project/python-crfsuite/) (Untuk Posttager)
#### 4. Program menggunakan python versi 3.
Contact me: [Gugun Mediamer](https://www.linkedin.com/in/gugun-mediamer-7a1088117)

---

### *Semoga Bermanfaat. Hidup hanya sekali, terkadang kesempatan datang tak berkabar, lakukan sebelum kau menyesal!* ![senyum](data:image/png;base64,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)
